# Sajeongjeon: dimensional reading guide

This is a concise route into the [building record](gbg-sajeongjeon.json), updated **2026-09-22**. That JSON owns the values and precise locators; this guide explains how they can inform a model without confusing a repair design with a survey. The record now contains **17 observations: six checked and eleven pending**. Pending linear records have visually checked transcriptions, but their unit convention or measuring basis remains unresolved.

## The useful dimensional set

| Attribute | Recorded annotation | Evidence and interpretation |
| --- | --- | --- |
| Repair plan, horizontal post-centre grid | 3.090 + 3.090 + 5.520 + 3.090 + 3.090 = 17.880 | Obs-010, printed 045; regular repair grid, separate from measured 033 |
| Repair plan, depth grid | 3.090 + 5.520 + 3.090 = 11.700 | Obs-010; same chain on section 050 |
| Plan area | **209.19 m²** | Obs-011; unit explicitly printed, checked transcription |
| Repair platform offsets | 1.830 outside each outer post-centre line | Obs-010; these are platform edges, not eaves |
| Section overall height | 13.250 | Obs-012, printed 050; exterior paving top to highest small cap above ridge assembly |
| Below-paving foundation extent | 600 | Obs-012; separate from the overall height |
| Section horizontal eave projection | 3.000 each end, split 2.370 + 630 | Obs-013; post-centre line to roof edge in this section, not a sloping member length |
| Central south opening | Width 4.623; vertical bands 487 + 335 + 2.740 | Obs-014, printed 017 detail ③; witness-line spans, not proven clear operable dimensions |
| Central north opening | Width 4.624; vertical bands 495 + 330 + 2.742 | Obs-015, printed 019 detail ⑪; preserve the differences |
| Repair floor boarding | T.42 | Obs-016, printed 045 and 050; board thickness, not total floor depth |
| Four interior posts in repair plan | Ø540 each | Obs-017, printed 045; measuring height/taper unresolved, not a perimeter-column default |

Periods in the linear annotations are preserved as printed; the raw JSON values collect their digits with `unit: null`. They have not been silently declared millimetres.

## A supported working metric interpretation

The repair plan's outer post-centre rectangle, interpreted as **17.880 m × 11.700 m**, gives **209.196 m²**. That differs by only 0.006 m² from the printed area. This is strong internal support for those physical spans, with the assumption that the area describes that rectangle. It does not reveal whether the notation uses decimal metres or grouped millimetres. See [drawing source note-006](../sources/src-gbg-sajeongjeon-measured-drawings-1993/source.json).

A first model could explicitly adopt this metric reading of the repair geometry, including a provisional **13.25 m** paving-to-cap height and **3.00 m** section eave projection. That transfers the supported convention from plan 045 to the matching section 050; it remains an interpretation, not a verified survey measurement. Opening and member annotations need their own basis recorded if the same convention is adopted. Such choices belong in the modeling brief, and need not prevent a complete building.

## Differences that must survive the handoff

The measured sheet 033 records unequal perimeter chains and separate upper measurements. Its page-bottom upper components sum to **17,830**, while the sheet prints **17,855**. A second public scan preserves both readings; it did not resolve the 25-unit discrepancy. Do not average the chains, regularize them to the repair grid or convert that discrepancy into a new “corrected” observation.

The clearer 045/050 images are additional scans of already retained sheets, not independent evidence. Their **보수** titles establish repair intent; they do not establish completion. Exact field dates, source-wide units and measuring heights remain unresolved. The overall section height is not floor-to-ceiling height, and the 4.600 intermediate segment has not been relabelled as a clear room or whole-column height.

The next connected check is the relationship among floor surface, base stones, column tops and ceiling supports. Opening operation and east/west boundaries also remain important. The 2014 report and native CAD are still unacquired; the new public drawings make useful progress possible without reopening the unchanged login barrier.
