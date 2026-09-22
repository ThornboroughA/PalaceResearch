# Project context and working decisions

This project supports a slow, enjoyable Korean-history study and making practice. Physical palace models provide a spatial overview; selected digital buildings, rooms, and objects make the studied spaces easier to understand. Useful subjects include how rooms connect, where people worked or waited, how an opening operates, and how a domestic or ceremonial activity fits into a building.

It remains a lower-priority personal project alongside the owner's studio work and *기록의 방*. Collection and experiments should leave reusable results without creating a weekly production obligation. An episode, a complete palace, and a finished modeling toolkit are not prerequisites for one another.

## Current scope

**Gyeongbokgung is the starting focus.** The supplied broader context brief discusses Donggwol as a long-term interest; the current conversation retains Gyeongbokgung as the practical first project. Gyotaejeon is an example and an existing empty record, not a required first acquisition or first model.

The supplied brief describes the wooden kits as approximately 1:250. That describes the intended physical overview, not a measured scale calibration of each kit. Research retains full-scale architectural dimensions. A model can be viewed at miniature scale or inspected closely without changing those source measurements. Any physical-kit fit or printing adjustment belongs in a separately recorded modeling variant.

The architectural focus includes both exterior form and useful interiors: room boundaries, floor changes, openings, supports, ceilings, roof structure, and connections. Sources on spatial use can accompany the geometry when relevant. Such accounts must retain their building, period, and evidential scope; geometry by itself does not establish a court practice.

**Modeling requirement, clarified 2026-09-22:** every commissioned building must become a complete, sensibly assembled Korean palace timber hall. Where building-specific evidence is missing, use explicit, revisable assumptions and suitable fallback construction. A highly accurate collection of parts with necessary components absent is a failed building outcome. This requirement applies throughout modeling; research uncertainty remains recorded without becoming a reason to omit required geometry or reduce the commissioned scope.

The immediate research priorities are **Sajeongjeon's dimensional attributes first**, followed by a layered, correctable body of knowledge for a generic Korean palace hall. The owner's “platonic ideal” is a working reference configuration to support modeling assumptions. Its relationships and alternatives should grow from inspected evidence and useful comparisons. Practical defaults can be adopted in modeling without being presented as measured historical facts. Broader modeling-workflow design is reserved for a separate discussion; [working ideas](brainstorming/complete-halls-and-fallbacks.md) are deliberately non-canonical.

## Two repositories, one traceable handoff

| Repository | Owns | Leaves to the other repository |
| --- | --- | --- |
| [PalaceResearch](README.md) | Source identities, acquisition records, architectural observations, uncertainties, historical states, and evidence comparisons | Art direction, mesh construction, shared modeling components, and production simplifications |
| [PalaceModeling](../PalaceModeling/README.md) | Model briefs, style decisions, editable Blender sources, construction methods, component revisions, and visual review | Authoritative historical measurements and source interpretation records |

A modeling brief cites the research building/state/observation IDs and the research revision it used. Any local dimension snapshot records that origin. A modeling problem can produce a focused research question, such as an opening's clear width or a ceiling datum. A new source finding returns to the research record; it does not get buried only in a Blender script.

The intended visual direction is mildly stylized and consistent across studies. That authorizes consciously documented production choices, not rewriting historical evidence to match a convenient part. Shared components should preserve adjustable interfaces and arise from successful reuse. Neither repository needs a universal palace module at the start.

## Shared understanding and presentation

The [architectural baseline](ARCHITECTURAL_BASELINE.md) holds a small, evolving body of shared understanding. Supplied books and articles enter the corpus as individual sources; they do not become a definitive body of skill instructions. New evidence and practical experience should refine both this understanding and any later workflow skill. The owner has deferred the visual guide while the research base grows.

The intended SNS audience is Korean, with a presentation that can celebrate Korean architectural character through recognizable buildings, spaces, and details. This gives source selection and interpretation a practical purpose while leaving specific visual decisions for later modeling work.

## Storage and maintenance

Research originals and binary derivatives live in Dropbox's `PalaceData`; Git holds their descriptions and recoverable references. There is no fixed 250 MiB acquisition limit and no Dropbox upload-confirmation workflow. Authored Blender files belong to Git LFS in `PalaceModeling`, as chosen by the owner.

Each repository has its own `NEXT.md`. Research may continue collecting while a modeling study waits for visual review; modeling may refine an established assembly while a source request is blocked. Shared direction should be revisited when evidence or the owner's preferences change, rather than inferred from an older attached conversation.

The [supplied background](context/README.md) preserves the wider ambitions. Engine integration and interaction-system design are outside this setup task.
