# 한국어로 한국사 — Palace Diorama / XR Study Project

## Project overview

This is a long-form Korean-history study and making project built around miniature palace architecture, lightweight XR, and Alexander's ongoing research into Joseon royal culture.

The project begins from a simple premise:

**study something → build a small physical or digital representation of it → use XR to make the historical idea visible**

Rather than producing conventional educational reels every week, the project develops slowly over time through physical model-making, 3D printing, Unity-based XR, historical reading, and occasional short-form posts. Each individual post can stay small and self-contained, while the overall system gradually accumulates into a reusable palace world.

The project should remain enjoyable as a hobby and useful as a research practice. It is not intended to become a second full-scale studio production alongside LEEBORO's client work or *기록의 방*.

## Relationship to 한국어로 한국사

`한국어로 한국사` is Alexander's Korean-language history channel, aimed primarily at a Korean audience.

Its central appeal is not that a foreigner is trying to act as an outside authority on Korean history. The stronger identity is:

**Alexander is seriously studying Korean history, and the mental picture he is building becomes visible in front of him.**

Earlier content focused more heavily on studying at a desk, books and notes, studio life, reflective narration, and regular edited reels about things Alexander had learned. That format communicated sincerity well, but required relatively high production effort and often made "Alexander studies Korean history" more memorable than the historical subject itself.

The current direction is lighter and more sustainable. Day-to-day study posts can remain simple: hands + book, short Threads posts, Instagram Stories, and brief comments on what is being read or reconsidered. More substantial posts should increasingly come from **making**, especially small XR or miniature-history experiments that can also reinforce LEEBORO's wider visual identity.

## Why this project exists

The project has several overlapping purposes.

### Reinforce real historical study

The project should grow out of research Alexander already needs or genuinely wants to do, especially Joseon palace culture, royal institutions, royal household life, court ceremony, spatial hierarchy, palace labor, movement and access, royal audiences, punishment and administration, food, service, domestic routines, childcare, writing, education, religion, and Lady Hyegyeong and the world surrounding *기록의 방*.

The models should encourage deeper understanding of how palace life actually worked in space. The project should not create large amounts of additional research obligation purely for content.

### Support *기록의 방*

Much of the research overlaps directly with *기록의 방 / Untitled, 1795*. The project can act as a lower-pressure research sandbox for understanding Donggwol, court roles and institutions, where people lived and worked, movement between palace spaces, domestic and ceremonial architecture, and how a human-scale event sits inside the larger palace system.

It should support the main work, not become a substitute for returning to it.

### Provide a sustainable history-content format

Rather than inventing a new history reel every week, the project offers a repeatable structure. A post might be one building, one room, one historical question, one palace process, one group movement, one object or prop, or one small XR interaction.

Different subjects can appear every few weeks without requiring a completely new technical foundation.

### Reinforce the LEEBORO brand

The project can occasionally cross-post to LEEBORO Story when the result is visually strong or technically interesting. It demonstrates XR, digital/physical mapping, spatial interaction, miniature-world design, 3D modeling, Unity development, 3D printing, historical reconstruction, and explanatory visualisation.

The studio benefit should remain understated. The historical study comes first.

## Physical direction

Alexander owns the Young Modeler / 영공방 wooden Gyeongbokgung series, including most of the major buildings and corridor sets, as well as a half-built hanok model.

The palace kits are approximately 1:250 scale.

At this scale, architecture reads clearly; palace layout and movement can be shown; groups and crowd-scale activity can work; but individual character acting becomes extremely limited. This makes the physical model especially suitable for routes, processions, queues, gathering, spatial hierarchy, circulation, building relationships, who occupies which zone, and where people wait or move.

Roofs should remain removable wherever practical. This makes the miniature more appealing as an object and allows interior digital scenes or physical inserts to become visible.

3D printing can supplement the wooden kits with missing buildings, replacement bases, altered façades, alternate roofs, interior floor inserts, walls and corridor pieces, historically specific structures, removable-roof locating systems, and custom palace modules.

## Donggwol as the long-term target

Although the physical kits are Gyeongbokgung models, the project's historical centre increasingly points toward **Donggwol — Changdeokgung and Changgyeonggung**.

This is because much of the Joseon history Alexander is most interested in, especially eighteenth-century palace life and Lady Hyegyeong's world, took place there.

Donggwol also has strong surviving historical documentation, `동궐도`, `동궐도형`, extensive palace scholarship, a more irregular terrain-responsive spatial structure, and direct relevance to the historical period of *기록의 방*.

The goal does not have to be an exact museum reconstruction from the beginning. A more practical approach is to develop Donggwol as a set of **modular precincts**: Injeongjeon courtyard, Seonjeongjeon, Huijeongdang, Daejojeon, Changgyeonggung residential areas, connecting corridors and gates, garden structures, and selected Hyegyeong-relevant spaces.

Some Gyeongbokgung kits may be used intact, modified, cannibalised for components, retained as standalone Gyeongbokgung studies, or replaced entirely by printed structures where conversion would be more difficult than rebuilding.

The project should not force every existing kit into a Donggwol equivalent.

## Historical accuracy standard

The project should distinguish between surviving architecture, archaeological evidence, contemporary textual evidence, historical paintings and plans, scholarly reconstruction, simplified explanatory reconstruction, and modern replacement buildings.

`동궐도` can serve as a major spatial reference, but it is not a perfect snapshot of every period relevant to Lady Hyegyeong.

For Hyegyeong-specific scenes, the project should verify whether the building existed in that period, its name had changed, its footprint or arrangement differed, or later fires or rebuildings altered it.

At miniature scale, not every bracket, roof ornament, or joinery detail needs to be reproduced. The details that matter most are:

- bay count (`간`);
- footprint;
- roof massing;
- platform height;
- attached wings;
- door/opening arrangement;
- relationship to neighboring structures;
- routes and access.

If a physical building is being used as a stand-in for a different historical site, that should be stated clearly and briefly.

## Digital twin concept

Because 1:250 is too small for meaningful character acting, the project should use a **two-scale visual language**.

At palace scale, the physical miniature acts as the overview. Tiny digital figures can show population, routes, crowd movement, hierarchy, waiting, processions, and spatial separation.

At human scale, selected rooms, groups, or characters can be pulled out into an enlarged digital twin. A user might tap a room, select a character group, remove a physical roof, highlight a section, or lift a space out of the palace. That selected element can then appear at a much larger scale for character interaction, object handling, ceremony, dialogue, work processes, serving, punishment, audiences, domestic life, or explanatory animation.

The physical palace shows **where** something happens.

The enlarged digital twin shows **what happens there**.

## Unity system direction

The project will use Unity.

The technical foundation should remain lightweight and reusable. Useful modular systems may include physical-model alignment / mapping, building and room selection, floating labels, route drawing, placeable props, simple character movement, crowd or formation placement, lightweight agent states, room highlighting, roof on/off state, digital zoom / pull-out scenes, comparison views, basic timelines, object enlargement, and small explanatory UI.

The goal is not to create a new bespoke interaction system for every post. Instead, the toolkit should grow gradually through real episodes.

## Character system

The project can slowly accumulate a reusable cast.

At palace scale, characters may be extremely simplified: sprites, very low-poly figures, simple walking loops, static poses, and group formations.

At enlarged scale, the same logical character can use a higher-detail model, readable clothing, stronger animation, gestures, props, and short interactions.

Character identity and behaviour should therefore be separated from visual representation. One historical role can have multiple representations depending on scale.

Possible recurring roles include king, queen, crown prince, crown princess, senior court ladies, palace women, eunuchs, officials, guards, servants, medical staff, kitchen workers, children, messengers, and craftspeople.

The cast should gradually reflect the full range of palace life, not disproportionately focus on elite women's appearance.

## Editorial principle

Each substantial post should ideally begin from a genuine shift in understanding:

**what I assumed → what I encountered in the source → what I now picture differently**

The physical or digital interaction should help explain that change.

The best subject is not necessarily the most visually elaborate one. Good recurring questions include:

- Who could enter this space?
- Where did people wait?
- How did an audience work?
- How was food carried into the palace?
- Who lived behind this wall?
- How many people were involved?
- What did punishment physically look like?
- Where were documents received?
- How did the royal household move between buildings?
- What was public and what was private?
- What changed between ceremonial and everyday use?

The key principle is:

**Ask not only what the palace looked like, but what it was like to live, work, wait, move, serve, rule, and endure inside it.**

## Production philosophy

This should be a long-running hobby/research project, not a weekly deliverable treadmill.

A useful rhythm is simple daily study maintenance on Threads / Stories; one substantial palace/XR study every few weeks; no requirement that every study session produce a post; and no requirement that every new post require a new app.

Each episode should ideally leave behind something reusable: one building, one digital room, one prop, one character, one movement behaviour, one interaction, one historical note, or one reusable UI element.

Over time, the project should **accrete** rather than reset.

## Relationship to LEEBORO Story

LEEBORO Story remains the studio's higher-priority SNS effort. The Romance Fantasy LBE is currently the main one-day-a-week team project.

This palace project should therefore remain mostly Alexander-led, use spare / hobby development time, reuse systems where genuinely useful, and avoid creating a second studio-wide production obligation.

Cross-posting to LEEBORO Story makes sense when an episode has an immediately readable visual idea, strong physical/digital interaction, clear craftsmanship, a surprising XR moment, or broader appeal beyond history enthusiasts.

The project can also act as a testing ground for systems relevant to LEEBORO's other work, but this should not become an excuse to over-engineer it.

## What success looks like

Success is not primarily measured by whether every post goes viral.

The project is working if, over time, it produces stronger understanding of Joseon palace culture, useful research for *기록의 방*, an expanding physical Donggwol / palace model, a reusable Unity explanatory toolkit, a growing library of characters and props, occasional strong history/XR posts, visible evidence of Alexander's sustained interest in Korean history, occasional useful client-facing demonstrations, and a project Alexander genuinely enjoys returning to.

The long-term result should feel less like a collection of disconnected SNS experiments and more like:

**a miniature Joseon palace world that becomes more historically informed, more populated, and more interactive as Alexander studies.**
