# PalaceResearch

A gradually growing architectural evidence collection, starting with **Gyeongbokgung**. Its main job is to find, retain, describe, and progressively inspect useful sources. Collection can continue between modeling sessions and does not have to finish one building before moving to another.

The collection supports a small Korean-history study and making project. The owner should be able to return after several weeks, understand what exists, and ask an agent to complete another useful batch. Read the [project context](PROJECT.md) for the relationship to physical miniatures and the sibling [PalaceModeling repository](../PalaceModeling/README.md).

## Start here

- **Returning to the project:** read [NEXT.md](NEXT.md), which contains the current checkpoint, a short queue, and a reusable task prompt.
- **Finding potential sources:** consult [LEADS.md](LEADS.md) for the supplied report, local corpus, both Drive collections, and candidates already spotted. Check this map and existing source records before searching or acquiring anew.
- **Doing research:** read [AGENTS.md](AGENTS.md), then [DATA.md](DATA.md) and the records affected by the task.
- **Interpreting architecture:** read the [architectural baseline](ARCHITECTURAL_BASELINE.md), a short, evolving guide tied to inspected sources. Update it when evidence changes a useful explanation; acquiring another book does not require expanding it.
- **Finding a building's evidence:** open its record in `buildings/` and follow the source and observation IDs.
- **Exploring future workflow choices:** [brainstorming/complete-halls-and-fallbacks.md](brainstorming/complete-halls-and-fallbacks.md) holds non-canonical ideas for complete models and gradually researched fallbacks. Confirmed priorities remain in `PROJECT.md` and `NEXT.md`.
- **Finding the original background:** use [context/README.md](context/README.md). Supplied chats and research reports are context and discovery leads, not verified architectural observations.

## What a useful session produces

Acquisition, indexing, and extraction are separate useful jobs. One session might retain two reports with good descriptions; another might locate interior drawings in a retained report; another might check a few measurements. A retained source needs a brief relevance and coverage note so that it can be found again. It does not need exhaustive processing before another source is admitted.

| Work | A useful stopping point |
| --- | --- |
| Discover | Identify a real document, its institution, catalogue record, relevance, and likely access route. |
| Acquire | Save an intact readable original in Dropbox, check its bytes and checksum, and record how to obtain it again. |
| Index | Identify selected useful plans, sections, tables, and interior drawings with exact locators and inspection status. |
| Extract | Add supported observations to the relevant building, keeping historical states and uncertainties distinct. |
| Compare | Connect documented examples, including meaningful differences, in [COMPARISONS.md](COMPARISONS.md). |

The default batch is defined in `NEXT.md`. Work is bounded by the chosen sources and inspection effort. There is no fixed 250 MiB download ceiling. Retaining a large report does not require processing the entire report in the same session.

## Files and ownership

Git holds the small, searchable record of the collection:

```text
README.md / PROJECT.md    Purpose, context, and relationship to modeling
AGENTS.md / DATA.md       Working rules and record conventions
NEXT.md                  Checkpoint and small prioritized queue
LEADS.md                 Wider source possibilities and supplied collections
COMPARISONS.md            Evidence-backed comparisons
ARCHITECTURAL_BASELINE.md Revisable understanding drawn from inspected sources
brainstorming/           Working proposals, separate from evidence and decisions
archive.example.json     Portable example of the local archive setting
context/                 Supplied background and recovered discovery links
sources/<source-id>/      Source metadata and selected useful text extracts
buildings/<building-id>.json
```

Dropbox holds original research files and binary derivatives, using the same stable source IDs:

```text
PalaceData/
    context/             Supplied binary background material
    sources/<source-id>/
        originals/       Unmodified PDF, CAD, images, or other acquired files
        derived/         Selected page images or conversions when useful
```

Folders appear when they have content. A report covering several buildings is retained once. Original Korean filenames remain in metadata even if a working filename is shortened.

## Dropbox location and recovery

The research archive belongs in **Dropbox**. Its current location is `D:\Dropbox (Personal)\Leeboro_Work\Internal\한국사\PalaceData`.

Resolve its root from `PALACE_DATA_ROOT` if set, otherwise from the ignored `archive.local.json` file's `dropbox_root`. A fresh checkout can copy [archive.example.json](archive.example.json) to `archive.local.json` and enter the current absolute path. This checkout is configured. Artifact records contain paths relative to that root, so moving the Dropbox folder requires changing only this setting. Verify the configured directory exists before writing; if it has moved, locate the existing `PalaceData` folder within the user's Dropbox and update the setting.

A locally readable, verified file in this folder is sufficient for the working collection. We do not track upload confirmations or audit Dropbox synchronization. If a file is missing later, use its catalogue/download route to reacquire it and compare the checksum; changed bytes may represent another version and must not silently replace the recorded original.

Research binaries stay out of Git and Git LFS. The sibling modeling repository uses Git LFS for authored Blender assets. Source URLs, titles, retrieval details, reuse statements, and checksums remain in Git so the research archive can be understood and recovered.

## Evidence priorities

Favor dimensioned plans and sections, column positions, room and partition arrangements, openings and their operation, floor and ceiling levels, and major structural relationships. Interiors are central to this project. Access and spatial relationships matter when a source explains how a room was used; a floorplan alone does not establish who could enter it.

Preserve the whole original, including material, decorative, and construction evidence that is lower priority today. Keep observations at full architectural scale. Measured facts, scholarly interpretation, and a later model's artistic simplifications remain distinguishable.

Gyeongbokgung is the active focus. Relevant comparative material can be retained without starting another palace project. Research can accumulate independently while `PalaceModeling` develops its own limited studies and shared construction methods.
