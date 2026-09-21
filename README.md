# Palace corpus

A slowly growing architectural reference collection, starting with **Gyeongbokgung**.
The immediate job is to collect reliable sources and extract traceable building data—not to build a palace generator.

This supports a low-priority, long-running Korean-history SNS project accompanying physical wooden palace models. Work should be useful in small, independently finishable batches. Publishing does not depend on finishing this corpus, a digital twin, or a complete toolkit.

## What we are working towards

1. **Building-specific reconstructions:** actual dimensions, documented layouts, and evidence for both interiors and exteriors.
2. **A reusable modeling vocabulary:** eventually, a consistent way to construct recurring parts and assemblies across buildings.

These are connected but not interchangeable. Historical observations belong here even when a later model deliberately simplifies them. A shared modeling component is a production decision, not proof that the original buildings were identical.

The initial artistic destination is mildly stylized, with weekly or fortnightly *building-production* work becoming feasible through accumulated reuse. That is a direction, not a guaranteed automated output or a requirement to publish a new building every week. The evidence collection must remain useful beyond miniature SNS reconstructions.

## Start here

- **Agents:** read `AGENTS.md`, then the current bounded task in `NEXT.md`. Consult `DATA.md` when creating records.
- **The owner returning after a break:** read `NEXT.md`. It should say what actually exists, what remains blocked, and the next useful action.
- **Looking up a building:** open its JSON in `buildings/`; follow its source IDs into `sources/`.

## Only two data folders

```text
README.md                 Purpose and navigation
AGENTS.md                 Working rules and guardrails
DATA.md                   Small record conventions and copyable examples
NEXT.md                   Current checkpoint, source leads, and one next task
COMPARISONS.md            Evidence-backed cross-building notes and questions
.gitignore
.gitattributes
sources/
    .gitkeep              Removed when the first real source is added
buildings/
    gbg-gyotaejeon.json    Empty first-target record, not researched geometry
```

Each acquired document gets one source folder, created only when needed:

```text
sources/<source-id>/
    source.json
    originals/            Unmodified acquired files
    derived/              Selected extracts/previews, only when useful
```

Keep a report once, even when it covers several buildings. Building records refer to it; they do not duplicate it. Do not create a directory for every palace, component type, research stage, or possible future feature.

`DATA.md` is a working convention, not a comprehensive architectural ontology. Extend it narrowly when real evidence requires something it cannot express.

## What deserves attention first

For the selected building, seek a dimensioned plan and useful sections, then record the column grid, room/partition arrangement, floor and ceiling levels, openings and their locations, and major structural/roof geometry. **Interior evidence is a first-class requirement**, not optional decoration after an exterior shell.

Preserve evidence on floors, ceilings, door operation, screens, materials, fittings, brackets, ornament, and associated structures when encountered. Prioritization governs what we inspect and extract first; it does not authorize deleting inconvenient or currently invisible detail from the source collection.

Work at full architectural scale in the data. Wooden-kit measurements, miniature display scale, and chosen artistic exaggeration are not measurements of the historical building.

## Originals and Git

This starter routes originals and binary drawing previews through **Git LFS**, while the JSON and Markdown stay ordinary text files. This is a storage choice for this repo, not permission for unlimited downloads or paid storage changes.

Once this directory is a Git repository and Git LFS is available, initialize its local hooks:

```sh
git lfs install --local
```

Before the first binary commit, verify that the attributes apply and that the intended remote can retain the files. Do not force originals into ordinary Git to work around unavailable LFS. Agents should continue catalogue/text work and report the storage blocker rather than install system software, change accounts, or buy storage unasked.

A separately authorized durable archive can also hold an original: record its stable URI/ID, checksum, and access conditions. An institutional download link alone, or a file in a disposable agent workspace, is not our retained copy. A private repo is the initial working assumption; do not change visibility or redistribute third-party sources without an explicit decision.

## Current contents and boundaries

The starter contains **no acquired reports, verified architectural measurements, or modeling code**. Gyotaejeon is a provisional acquisition target drawn from the owner's example, not a commitment about the first wooden model to build.

Gyeongbokgung is the default focus. Other palaces or architectural traditions are admissible when a specific source or comparison directly helps the current task—not as parallel projects.

Do not add Blender/Unity scaffolding, a component library, a database, a search service, a separate toolkit repository, or an automation framework now. Add the next piece when actual work needs it.
