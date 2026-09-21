# Agent instructions

## Mission and scope

Build a small, reliable, incrementally useful **architectural evidence corpus**. Start with Gyeongbokgung. The owner has limited time and must be able to understand the repository after weeks away.

Read `README.md`, `NEXT.md`, and the affected records before working. Follow an explicit user task; otherwise use the bounded acquisition batch in `NEXT.md`. Finish that batch and stop. A large eventual corpus is not authorization to crawl everything or build its future tooling.

For now, collect sources, inspect relevant drawings, extract building data, and record useful comparisons. Do not generate models, decide a universal palace module, or turn this into a second major studio project.

## Evidence is not a modeling recipe

- Preserve originals unchanged. Keep derived text, page images, conversions, and annotations separate and traceable to an original artifact.
- Store what the evidence supports, including differences between buildings. Never round or standardize historical observations to match a convenient shared asset.
- Prioritize building geometry and **interiors**: room arrangement, partitions, openings and their operation, column positions, floor/ceiling levels, and major structural relationships. An exterior-only record is not a complete building record.
- Do not exhaust the task budget on fine bracket/lattice ornament while basic plans, sections, or interior boundaries remain unprocessed. Preserve the relevant source/detail references for later.
- Do not discard material, decorative, construction, or relational evidence merely because the current tabletop model may hide it.

## Acquisition

Prefer primary measured surveys, repair/restoration reports and drawings, then relevant academic analysis. Treat catalogue descriptions as leads, not inspected document contents. Preserve Korean titles and technical terms alongside useful English descriptions.

For each candidate, check for an existing record and duplicate files. A document covering several buildings has one source record. Verify the actual downloaded file: content type/header, readable content, byte size, and SHA-256. Login/error HTML, an LFS pointer, and a zero-byte response are not a downloaded PDF or CAD drawing.

Record the institution, exact title, publication date when known, catalogue URL, download route, and stated reuse conditions. Do not invent bibliographic details or assume public access means unrestricted redistribution. Do not apply a blanket source license. Respect access restrictions; do not bypass logins/paywalls or run untrusted scripts/macros contained in acquired material.

Check the repo's binary-retention route before a large download or commit. Use the configured LFS route or an explicitly authorized durable archive. Record local-only originals honestly; never imply that an ephemeral workspace or an unpushed LFS object is safely archived. Do not purchase storage, change remote settings/visibility, or install system software without authorization.

## Extraction and verification

Start with native text/vector/CAD access and visually inspect relevant drawings. Keep the original CAD even after conversion; do not treat a raster trace or converted file as newly authoritative CAD. Use OCR only when other access is inadequate, on selected pages; do not bulk-OCR whole Korean reports by default. An uncertain character or digit stays uncertain.

Each architectural observation needs a precise source locator, an extraction method, and a verification status. For PDFs use **one-based PDF page numbers**, distinct from printed page labels and drawing numbers. Cite the original artifact even when reading a derivative.

Do not confuse:

- publication date with survey date or the date of the depicted building;
- a surveyed condition with a proposed restoration, demolition plan, or hypothetical reconstruction;
- an explicit dimension with a quantity measured from drawing geometry or estimated from a scan;
- a column-centre spacing with clear room width, a frame's outside size with its clear opening, or plan distance with a sloping member's length.

Record measurement endpoints/basis, units, datums, and orientation whenever relevant. Use full-scale architectural dimensions. No unverified universal bay size, paper-scale conversion, historical-foot conversion, or wooden-model-derived building dimension.

Do not calculate geometry from pictorial images as though they were measured plans. A printed scale alone is not a calibration for a resized scan. Geometric derivations or scaled estimates need their inputs, calibration/assumptions, and uncertainty; keep them distinguishable from annotated dimensions.

Keep historical states separate. Allow an unresolved state; do not silently assume every drawing in one report shows the same state. Conflicting observations remain separate and cross-referenced until resolved. Do not average them or silently replace the less convenient value.

Unknown is `null` or an explicit gap, not zero, an invented standard, or a copied value from a neighboring building. `checked` requires an actual verification action recorded in the observation; running a text parser is not visual checking. Do not claim human review for agent work.

Preserve source terminology and evidence for relationships: which room an opening serves, where a floor assembly changes, how a partition meets a bay, or which examples a comparative study actually covers. Do not infer universal applicability from a generic architectural description.

## Minimal records and comparisons

Use `DATA.md` conventions. Keep factual values in the appropriate building record, with stable observation IDs. General source findings can remain source notes with exact locators; do not force them onto an unverified building.

Use shared topic labels for discovery, not rigid module categories. Put cross-building comparisons in `COMPARISONS.md`, referencing the observations/source locators and stating differences, scope, and unanswered questions. A candidate resemblance is not an approved component family or a modeling default.

Create folders only for actual content. Do not pre-generate dozens of empty building records, schemas, role files, scripts, or indexes. Use temporary helpers in ignored scratch space; add permanent tooling only when a concrete repeated need justifies it. Preserve existing IDs and user edits. Explain a necessary convention change in `DATA.md`; do not reorganize the repo incidentally.

## Before finishing

Validate JSON syntax and inspect the diff. Check IDs/references, artifact existence and checksums, page locators, unit/state ambiguity, and the distinction between checked and pending observations. For acquired binary files, distinguish local retention from confirmed remote/archive retention.

Update the small checkpoint in `NEXT.md`: what exists, the next useful task, and any blocker. No sprawling session diaries. Report documents acquired versus merely found, observations checked versus pending, important interior gaps, and whether originals are durable or local-only. A clean partial result with a clear next step is a successful batch. Do not claim completeness or accuracy for uninspected pages or an unfinished building.
