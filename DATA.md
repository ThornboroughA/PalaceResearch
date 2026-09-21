# Data conventions, v0

Two record types: a **source** and a **building**. Everything below is a starter convention, not a schema engine. JSON examples are templates, not researched facts; do not copy placeholder observations into the corpus.

## IDs, files, and paths

Use stable, readable IDs. Building IDs include a palace prefix, such as `gbg-gyotaejeon`. Source IDs start with `src-` and a short descriptive slug. Do not rename an ID just because a title/date is later clarified.

A source lives at `sources/<source-id>/source.json`. A building lives at `buildings/<building-id>.json`. Artifact paths are **relative to their source folder**. Use UTF-8 and preserve original Korean filenames in metadata, even when a local filename is shortened.

One source record normally represents one document/edition/drawing set, not an entire website. Separate editions or materially different surveys should not silently replace each other. A portal/folder URL in `NEXT.md` is a discovery route, not an acquired source.

## 1. Source record

Copy this only when a real document or drawing set has been identified:

```json
{
  "id": "src-replace-me",
  "title_ko": null,
  "title_en": null,
  "creators": [],
  "publisher": null,
  "publication_date": null,
  "evidence_kind": null,
  "catalog_url": null,
  "building_ids": [],
  "topics": [],
  "access": {
    "status": "catalogued",
    "last_attempt": null,
    "note": null
  },
  "rights": {
    "statement": null,
    "url": null,
    "redistribution": "unknown"
  },
  "artifacts": [],
  "sheets": [],
  "notes": []
}
```

`evidence_kind` describes the source: for example `measured_survey`, `repair_report`, `restoration_proposal`, `academic_analysis`, or `historical_visual`. It does not automatically validate every claim inside it. Preserve the publisher name printed in the source; label your own English title translations as translations, not official titles. Record a mixed report as such; determine the state and purpose of individual drawings separately.

`access.status` may be `catalogued`, `downloaded`, or `blocked`. Downloaded does not mean inspected or durably archived. Use ISO dates only when the actual date is known; preserve a year-only source as a year-only string.

Add one artifact entry for each file actually held:

```json
{
  "id": "original-01",
  "role": "original",
  "path": "originals/report.pdf",
  "original_filename": null,
  "retrieved_from": null,
  "retrieved_on": null,
  "media_type": null,
  "bytes": null,
  "sha256": null,
  "storage": "git_lfs",
  "archive_uri": null,
  "retention_status": "local_only"
}
```

For a real artifact, fill the verified byte count/hash and retrieval details. `storage` is `git_lfs`, `git`, or `external_archive`; originals use LFS or an authorized archive. `retention_status` is `local_only` until the original has actually reached its remote/archive, then `durable_confirmed`. Record how retention was checked. With an external archive, retain its stable file ID/URI rather than a temporary signed URL; a local cache path may be null.

A derived artifact additionally records `parent_artifact_id` and `processing`: the selected original pages, extraction/conversion method, tool/version when available, and crop/DPI/unit transforms as applicable. Give each derivative its own checksum. Keep useful text ordinary Git; binary previews use the LFS attributes. Do not generate every possible derivative on first acquisition.

### Drawing sheets

Index selected useful sheets in `sheets`, rather than splitting every report into hundreds of files:

```json
{
  "id": "sheet-001",
  "artifact_id": "original-01",
  "pdf_page": null,
  "printed_page": null,
  "sheet_label": null,
  "title_ko": null,
  "kind": "plan",
  "building_ids": [],
  "topics": [],
  "has_dimensions": null,
  "documented_state": null,
  "inspection": "uninspected",
  "preview_artifact_id": null
}
```

`pdf_page` is a one-based integer. `printed_page` and `sheet_label` are strings preserving the source's labels. `kind` may be plan, section, elevation, reflected-ceiling plan, detail, etc. `has_dimensions` remains null until checked. `inspection` is `uninspected` or `visually_inspected`; state exactly what was inspected in a note when needed. A report's drawing contents/index may supply leads without proving a sheet's actual details.

Use optional locator fields for CAD layout/layer/entity handles, image region, table row, or webpage heading when applicable. Do not invent page numbers for unpaginated sources.

`notes` can hold general construction findings, scope limitations, or material useful beyond the current building. Such findings need a text statement, topics, and the same precise evidence locator used below. Record the population/period the source actually discusses; a general note is not a measurement of every linked building.

## 2. Building record

The starting `buildings/gbg-gyotaejeon.json` is an empty example of a real target record. `source_ids` are relevant sources, not blanket citations for all its data.

Add entries to `states` only as evidence requires. Each state needs an ID, a description of what is depicted, and supporting source locators. Include a date/date range only when supported. A modern report can contain several states. An observation with unresolved chronology keeps `state_id: null`; describe the uncertainty.

Add entries to `elements` only for parts that need to be identified: a room, bay, opening, wall run, platform, roof, or structural member. Each needs an ID and descriptive label; retain the source's label/Korean term where available. An analyst-assigned ID is just a reference, not a claim that the source names that room.

Add observations incrementally:

```json
{
  "id": "obs-001",
  "subject": "building",
  "topics": ["column-grid"],
  "property": "bay_width",
  "value": null,
  "unit": null,
  "as_recorded": null,
  "state_id": null,
  "measurement_basis": null,
  "method": "transcribed_dimension",
  "verification": "pending",
  "evidence": [
    {
      "source_id": "src-replace-me",
      "artifact_id": "original-01",
      "sheet_id": null,
      "pdf_page": null,
      "printed_page": null,
      "locator_note": null
    }
  ],
  "review_note": null,
  "notes": null
}
```

For actual observations:

- **Subject and value:** `subject` is `building` or a local element ID. `value` may be a number, text, boolean, ordered list, or structured object. Preserve labels and order in grids/room lists; an unlabeled bag of dimensions is not a floorplan.
- **Units and basis:** prefer full-scale millimetres for verified modern linear dimensions, with the exact source transcription in `as_recorded`. Record conversion basis when needed. Preserve unresolved historical units rather than inventing a conversion. State centre-to-centre versus clear opening versus outside frame, and the datum for heights. Angles use degrees; counts may use `count`; qualitative observations use null units.
- **Coordinates:** only add positions after recording the origin, axes/orientation, datum, units, and transformation from the source. A facade view and a floorplan need not share axes. Do not fabricate an entire coordinate grid to fill gaps in one measured row.
- **Method:** distinguish `transcribed_dimension`, `source_statement`, `measured_geometry`, `scaled_estimate`, and `interpretation`. Estimates/derivations retain inputs and uncertainty. A confirmed transcription can still describe a conjectural historical reconstruction; verification does not upgrade that source's evidential basis.
- **Verification:** `pending` or `checked`. A checked observation requires a review note describing the actual check and whether it was by an agent or a human. Machine extraction alone does not establish correctness. For a doubtful reading, keep the candidate/ambiguity in notes instead of silently choosing a digit.
- **Evidence:** cite the original artifact and precise page/sheet/detail/table/CAD locator. Reference derivative previews additionally, not instead of the original. Several independent sources can support the same observation, but contradictory values require separate observations.

Do not add null-valued observation rows merely to satisfy a checklist. Unknowns belong in `gaps` until there is something meaningful to record. Conversely, do not omit an observed relationship just because it is not numeric: room adjacency, an opening's host wall, a floor-type boundary, or the sequence of assemblies may be essential evidence.

For a relationship, use the same observation form with a clear property such as `opens_into` and a value such as `{"element_id": "room-02"}`. Cross-building references use `building-id#element-id` or `building-id#observation-id`. This is not a requirement to build a scene graph or a full component taxonomy.

## 3. Cross-building discovery without a second database

Reuse topic labels where they fit: for example `column-grid`, `interior-layout`, `openings`, `floor-assembly`, `ceilings`, `roof-structure`, and `brackets`. Add a label when needed; these are search aids, not historical classifications.

Keep comparative findings in `COMPARISONS.md`. Link to source observations, identify the buildings/states and dimensions actually compared, and retain differences and exceptions. Prose with stable references is sufficient for v0. A later machine-readable comparison file can be added when a real analysis needs it; do not duplicate authoritative measurements in an unsynchronized second table now.

Stylistic compromises and accepted modeling recipes do **not** belong in these historical observations. When modeling begins, give those decisions their own small document rather than rewriting the evidence.
