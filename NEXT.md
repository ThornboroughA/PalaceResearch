# Next task and checkpoint

## Current checkpoint

- Focus: Gyeongbokgung, one building at a time; interior evidence matters as much as exterior geometry.
- Present: repository instructions and an empty `gbg-gyotaejeon` target record.
- Acquired originals: none. Extracted architectural observations: none.
- Binary storage: LFS attributes supplied; the actual working environment and remote still need checking. No archive/upload has been tested by this starter.
- Next: one bounded acquisition trial. Gyotaejeon is the provisional target because the owner used it as an example; substitute another building when explicitly selected.

Replace this checkpoint after a batch. Keep it brief and accurate; do not accumulate an activity diary.

## Source entry points

These are discovery routes supplied by the owner, **not verified claims about the contents of a specific report**:

- Research folder: <https://drive.google.com/drive/folders/1ptj5lfQdVq7s3tii98QkX5hSXWByGJck?usp=sharing>
- Heritage Portal record: <https://www.heritage.go.kr/heri/cul/culSelectDetail.do?ccbaCpno=1121108160000&pageNo=1_1_2_0>

Use the connected Drive tools when available for the folder. Otherwise record the access limitation and continue with public institutional sources; do not bypass authorization. Inventory only what is relevant to the chosen building/task. Verify which building the portal record actually concerns rather than assuming it is Gyotaejeon.

No deep-research report or source PDFs are bundled here. Earlier conversational examples of report titles, dates, drawing numbers, and measurements are **not** verified records. Check actual catalogues/documents before ingesting them.

Useful initial search queries—not asserted publication titles:

```text
"경복궁 교태전" 실측
"경복궁 교태전" 수리보고서
"경복궁 침전" 복원 보고서 도면
"교태전" 평면도 단면도 창호
```

Search institutional catalogues, including records under both 국가유산청/문화재청 and 국립문화유산연구원/국립문화재연구소 names. Prefer a relevant dimensioned report over an indefinite hunt for native CAD. A comparative source belongs in the batch only when it helps the current building/interior question.

## First acquisition batch

This is a small trial of the capture process, not a pilot reconstruction or a survey of ten buildings.

**Default bounds:** at most three relevant source documents; at most 250 MiB of new original downloads and ten selected drawing-page derivatives. These are conservative project defaults, not platform limits. Do not attempt full-report OCR or bulk CAD conversion. Limit repeated failed access attempts to two per source before recording the blocker and moving on. A user-specified budget can replace these bounds for later batches.

1. Check existing records and the original-retention route. Identify the best accessible primary source for Gyotaejeon's dimensions and interiors. Catalogue a small number of genuine alternatives where useful.
2. Acquire at least one relevant original when access and storage permit. Preserve bytes, retrieval details, checksum, and stated rights. Mark local-only retention honestly until a remote/archive copy is confirmed.
3. Inspect and index the most useful plan, section, and interior/opening sheets. Include exact locators and which state each appears to document. Extract only useful page previews/text; keep the rest of the report intact for future work.
4. Record a small checked subset of observations in the building JSON—roughly 5–15 *only when supported*. Prefer column/room arrangement, interior openings, floor/ceiling levels, and measured dimensions. Do not force a quota or substitute decorative minutiae for missing geometry.
5. Record significant gaps. Capture an evidence-backed cross-building comparison only if one naturally appears in the chosen material; otherwise leave `COMPARISONS.md` unchanged.
6. Validate records/references and the diff. Update this checkpoint and name one next useful task. Follow the authorized branch/commit workflow; do not change repository settings or publish unasked.

A useful result can be one retained report, a handful of well-located sheets, several checked observations, and a clear next step. If acquisition is blocked, a genuine catalogue record plus precise blocker and alternative route is still useful. Do not describe that result as an acquired source or a finished building.

## Reusable prompt

> Read README.md, AGENTS.md, DATA.md, and NEXT.md. Run one bounded acquisition batch for the current Gyeongbokgung building, using NEXT.md's bounds unless I provide another budget. Prioritize measured geometry and interiors. Preserve originals, index selected useful sheets, and add only traceable observations. Keep unresolved states/units/readings explicit. Do not build models, infer a universal kit, expand the folder hierarchy speculatively, or broaden to other palaces. Update NEXT.md with what actually exists, storage/access blockers, and one next useful task. Report acquired versus merely located sources and checked versus pending observations.
