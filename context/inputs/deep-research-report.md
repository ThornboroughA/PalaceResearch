# Architectural Reference Corpus for Reconstructing Gyeongbokgung and Changdeokgung

## Research conclusions

For the kind of work you are proposing, the most useful source base is much better than a collection of published floor plans. Korea Heritage Service and its predecessor agencies have commissioned **precision measured surveys (정밀실측조사), repair/disassembly reports (수리보고서 / 해체실측수리보고서), restoration reports (복원·중건공사보고서), archaeological reports, 3D scans, and raw CAD drawings** for a surprisingly large number of individual palace buildings. The current **Korea Heritage Digital Service / 국가유산 디지털 서비스** is becoming the central clearinghouse for these materials. Its records can be filtered specifically by 3D, drawings, reports, images, and other media; for researchers, designers and developers it explicitly recommends obtaining the original files rather than only viewing derivative JPEGs. citeturn17search1turn16search2

This changes how I would approach the historical research. Rather than attempting to infer a generalized “Joseon palace module” from photographs, I would first construct a corpus from **measured buildings**, and only afterward use historical drawings and architectural scholarship to establish which characteristics are reusable and which are particular to one building or period. This is especially important because the physical palaces seen today do not represent a single historical moment: some buildings are surviving nineteenth-century structures, some have undergone substantial repair, some are twentieth-century reconstructions, and some—particularly Changdeokgung's Daejojeon/Huijeongdang area and reconstructed portions of Gyeongbokgung—need to be treated very carefully when the target is “Joseon architecture” rather than simply “the building as photographed today.” citeturn13search2turn18search6

For your project, I would divide the evidence into four evidentiary layers:

| Evidence layer | Best material | What it establishes |
|---|---|---|
| **Measured geometry** | 정밀실측조사보고서, DWG, 3D scan | Actual bay spacing, column dimensions/positions, foundations, elevations, roof geometry, timber framing, doors/windows, floors, ceilings |
| **Construction evidence** | 수리보고서, 해체실측수리보고서, 복원공사보고서 | Hidden joints, member sections, wall/floor build-up, ondol, replacement history, construction sequence |
| **Historical state** | 북궐도형, 동궐도, 동궐도형, early photographs, colonial-era plans, Uigwe | What existed at a particular date; lost corridors, room arrangements, doors, floors, subsidiary buildings |
| **Interpretive scholarship** | architectural-history papers and theses | Resolves conflicts between present form, restoration decisions and historical evidence |

The richest immediate starting points I found are **Gyeongbokgung's Sajeongjeon–Cheonchujeon measured-survey corpus** and **Changdeokgung's Nakseonjae–Seokbokheon–Sugangjae measured survey**. Between them you get ceremonial/administrative halls and comparatively domestic royal architecture, including measured columns, beams, bay dimensions, windows, floors, roofs and interior divisions. They are much closer to the “data corpus” you described than ordinary palace books. citeturn13search1turn16search0

Your existing Drive collection is also worthwhile, but its greatest value is not raw dimensions. The strongest items there are **interpretive control documents** explaining how present conditions differ from earlier ones. The Seonjeongjeon article, for example, argues from documentary evidence that the current side openings and flooring do not faithfully represent its earlier ceremonial arrangement; the two Woo/Kee papers establish major 1908 and 1920 transformations around Injeongjeon and the inner palace. Those are exactly the sorts of papers that prevent a very accurate 3D model of the *wrong historical state*. fileciteturn1file0L2-L2 fileciteturn2file0L2-L2 fileciteturn3file0L2-L2

## The core archive to mine first

### Korea Heritage Digital Service

The single most valuable online resource I found is **국가유산 디지털 서비스 (Korea Heritage Digital Service)**. It is substantially more useful for your purposes than a conventional Heritage Portal monument page because it exposes the products of individual survey, documentation and digitization projects. The site's media filters explicitly distinguish **3D, image, drawing, report and multimedia** records, and individual heritage pages connect to the projects that created those records. citeturn17search1turn16search2

The official documentation says that researchers, designers and developers should use the **original files**, while lighter derivative files are intended for ordinary browsing. Some originals can be downloaded normally; larger datasets require a data request. The service even gives “game map/building/background design using traditional architecture” as an example of an acceptable stated use, which is unusually close to your intended workflow. citeturn17search0turn17search2

This is not merely a photograph archive. KHS describes its precision records as including three-dimensional measurements, drawings, photographs, reports and video, with source geometry acquired by laser scanning to millimeter-scale precision. That does not mean every palace asset is equally detailed, but it establishes the intended accuracy of the high-end `3D 정밀데이터` class. citeturn17search4

Licensing has to be checked **asset by asset**. The service uses Korea's Public Nuri/KOGL licensing categories. Type 1 permits commercial and non-commercial reuse, modification and redistribution provided attribution is given; other types add non-commercial and/or no-derivatives restrictions. Thus the corpus is excellent for internal dimensional reference, but you should preserve the license field when your agents ingest each record rather than assuming the entire archive has identical rights. citeturn16search1

A useful practical distinction in the KHS data is between:

**Measured-survey source material** — what I would regard as the strongest geometry evidence; and

**content-oriented 3D assets** — useful for comparison, orientation or checking a reconstruction, but not necessarily a substitute for measured drawings and reports.

For a data-derived architectural corpus, the former should be authoritative where available.

### What a good KHS project actually contains

The **2014 `경복궁 사정전 일곽 정밀실측 설계용역`** illustrates just how deep these datasets can be. It covers precision measurement of Sajeongjeon and Cheonchujeon and simpler measurement of Manchunjeon, Sajeongmun and associated corridors; the project page reports **865 associated records**. citeturn12search2

The attached records include things such as stair details and measured rafter/eave drawings as DWGs, while other pages of the same project expose elevations, sections, roof plans, reflected/ceiling plans and ordinary plans. citeturn12search4turn12search5turn12search6

The associated 727-page report is even more important. Its contents include tables of measured:

- bay spacing,
- foundations/platforms,
- base stones,
- columns,
- changbang and pyeongbang horizontal members,
- major and secondary beams,
- roof and tile curvature,
- and a study of the historical construction unit or **yeongjocheok (營造尺)**.

It then provides 3D-scan imagery and measured drawings beginning in the appendix. citeturn13search1

That is essentially the ideal source format for the corpus you described: numerical measurements + analytical explanation + conventional architectural drawings + scan-derived geometry.

### National Assembly Library and National Archives

The **National Assembly Library** is an important parallel access point because its catalogue entries often expose extremely detailed tables of contents for official survey reports and, for many titles, offer full-text viewing or downloads. The Sajeongjeon report and Nakseonjae report are both catalogued with their detailed measurement sections and downloadable electronic resources. citeturn13search1turn16search0

The **National Archives of Korea** should also be searched by exact Korean report title. For example, it holds `창덕궁 희정당 신관 실측,수리보고서`, produced by the Cultural Heritage Administration in 2003, as a permanently retained government publication with an original-view option. citeturn19search9

Those repositories matter because a report absent from the current KHS interface is not necessarily unavailable.

## Gyeongbokgung reference stack

Gyeongbokgung presents two different research problems. Its major surviving nineteenth-century monuments such as Geunjeongjeon and Sajeongjeon can be measured directly against extensive modern survey documentation; many residential and subsidiary structures, however, were dismantled, destroyed or reconstructed in the twentieth century. For the latter, restoration reports and historical plans are just as important as current measured geometry. KHS's own palace chronology records, for example, the 1995 reconstruction of Gangnyeongjeon and its east/west corridors and the later reconstruction programs in other precincts. citeturn12search7turn13search2

### Sajeongjeon, Cheonchujeon and Manchunjeon

This should be one of your first acquisition packages:

**`경복궁 사정전 일곽 : 정밀실측조사보고서` — Cultural Heritage Administration, 2014.**

It is exceptionally relevant because Sajeongjeon and Cheonchujeon give you closely related buildings surveyed to a common methodology. The report contains measured bay tables, platform dimensions, base stones, columns and numerous structural members, as well as measured drawings and 3D scans. citeturn13search1

KHS classifies Sajeongjeon as a five-bay-front by three-bay-side, hipped-and-gabled, double-eaved building with a multi-cluster bracket system and a two-high-column/seven-purlin frame. That sort of metadata is useful as an index, but the report and DWGs should be treated as the actual geometry evidence. citeturn13search4

The same survey project includes Cheonchujeon and Manchunjeon. This is particularly valuable comparatively because historical sources indicate that the flanking halls had different thermal/interior arrangements from Sajeongjeon; the detailed report lets those functional differences be tested against measured construction rather than inferred visually. citeturn12search2turn13search4

There is also unusually useful historical plan evidence for the flanking halls. The Joseon Royal Annals Dictionary's architectural entry for Cheonchujeon cites the **Bukgwoldo-hyeong** as recording six bays by four bays, with six-cheok perimeter bays and eight-cheok inner bays, a two-bay central hall, rooms at either side and a mixture of floor and heated-room zones. Manchunjeon is recorded with the same basic bay scheme. These figures should not supersede modern measured dimensions, but they are valuable evidence for intended nineteenth-century planning dimensions. citeturn21search2turn21search5

### Geunjeongjeon

The KHS entry identifies the present Geunjeongjeon as the 1867 reconstruction: five bays by five bays, two storeys, hipped-and-gabled double eaves, multi-cluster brackets and a two-high-column/eleven-purlin framing system. The page also links the building to a **2003 nationally designated wooden-palace architecture measurement project**. citeturn13search3

More importantly for your purposes, the Digital Service contains raw/detail drawing families for Geunjeongjeon. The available search records include foundation/woldae details, column-seat and bracket-member details, high-column drawings, bracket layouts, eave-curvature studies, structural framing drawings, window/door details and component cross-sections. citeturn5search0turn5search1turn5search3turn5search4turn5search6turn5search10

For the platform itself, add:

**`(2023) 경복궁 근정전 월대 보수공사 : 수리보고서`.**

This 423-page KHS report includes historical and measured analysis of the woldae, comparison of early- and late-Joseon dimensions, a yeongjocheok analysis, measured component tables, construction records and repair drawings. citeturn13search0turn14search6

This is a good example of why repair reports deserve to be in the corpus even when you do not plan to model every stone: they often contain better geometry and chronology than general architectural descriptions.

### Gangnyeongjeon, Gyotaejeon and the residential core

This precinct needs a different source hierarchy because the present Gangnyeongjeon is a modern reconstruction. KHS's chronology records that material from Gyeongbokgung's inner palace was transferred for the reconstruction of Changdeokgung after the 1917 Daejojeon fire, and that Gangnyeongjeon and related elements were reconstructed at Gyeongbokgung in 1995. citeturn13search2

The historical architectural description is nonetheless exceptionally useful. The Royal Annals Dictionary gives Gangnyeongjeon as effectively eleven bays across including side toenkan and five bays deep including front/rear perimeter bays. It describes a central three-bay maru, ondol rooms on both sides and perimeter wooden flooring, and specifically cites `경복궁배치도`, `북궐도형` and `조선고적도보` as evidence for the late-nineteenth-century form. citeturn21search11

Gyotaejeon similarly has a documented historical building type; the Sillok dictionary records it as nine bays by four and identifies its association with the queen's residential precinct. citeturn20search5

For these buildings I would therefore collect, in this order:

1. the **1990s Gyeongbokgung restoration documentation** and restoration design drawings;
2. **Bukgwoldo-hyeong / Gyeongbokgung baechido**;
3. surviving pre-dismantling photographs and `조선고적도보`;
4. current building survey/digital records;
5. the Changdeokgung Daejojeon/Huijeongdang documentation, because materials and architectural forms from the Gyeongbokgung inner palace became entangled with the Changdeokgung reconstruction after 1917. citeturn13search2turn21search11

This ordering avoids treating a twentieth-century reconstruction as an independent primary witness to the nineteenth-century building.

### Bukgwoldo-hyeong: indispensable palace-wide evidence

For palace-scale reconstruction, **`북궐도형 (北闕圖形)`** should be near the top of your Gyeongbokgung corpus.

It is not simply a picturesque map. It is a large architectural layout drawing produced after the nineteenth-century reconstruction of Gyeongbokgung. The sheet is divided by a regular red grid, and the buildings are drawn against it. Individual rooms are labelled by function—such as room, hall, kitchen and gate—and major structures include annotations for items such as bracket type, number of bays, column height and column spacing. citeturn21search0turn21search1

That makes it exceptionally useful for your purposes even when a demolished building has no modern measured survey.

It should, however, be used as **historical dimensional evidence rather than treated like a modern survey**. Its geometry can be calibrated against surviving buildings whose actual dimensions are now known. That comparison is precisely the kind of downstream analysis your Codex corpus should be able to perform.

The related primary/historical plan set worth collecting is:

**`북궐도형`**, **`북궐후원도형`**, **`경복궁배치도`**, **`경복궁고도`**, **`궁궐지`**, and relevant diagrams in ceremonial Uigwe. The scholarly Gyeongbokgung entry explicitly uses these sources together rather than assuming one document provides a complete history. citeturn21search3

### Restoration and excavation corpus

The AKS/Hanyang digital-humanities project provides a very useful bibliographic map of the Gyeongbokgung restoration literature. Its inventory includes, among others:

`경복궁 복원기본계획`  
`경복궁 사정전 권역 수리보고서`  
`경복궁 사정전일곽 정밀실측보고서`  
`경복궁 소주방권역 중건보고서`  
`경복궁 자경전 및 자경전 십장생 굴뚝 실측조사보고서`  
`경복궁 태원전 권역 중건보고서`  
`경복궁 함화당·집경당 권역 보수복원공사 보고서`  
`경복궁발굴조사보고서 — 소주방지, 흥복전지, 함화당·집경당 행각지`  
`경복궁 동궁지역 중건공사보고서`  
`경복궁변천사`  
and a translation of **`경복궁영건일기`**. citeturn20search0turn20search1

These are exactly the reports to seek out when you move beyond the first half-dozen major halls. Excavation and reconstruction reports are particularly important for **haenggak, corridors, kitchens, stores, gates and vanished support buildings**, which are underrepresented in tourism-oriented books but highly relevant to producing convincing architectural volume.

For Jagyeongjeon, KHS records a dedicated **2010 precision-survey project**, including a formal survey report. citeturn12search0turn12search1

For Jibokjae, the architecture bibliography records both a 1982 repair report and the 2005 **`집옥재: 수리조사보고서`**, which is useful because Jibokjae represents a deliberately atypical late-nineteenth-century palace building and therefore makes a good negative/control case against overgeneralizing a standard Joseon module. citeturn21search13

## Changdeokgung reference stack

Changdeokgung is in some respects the richer architectural research target because there are surviving halls of quite different dates and functions, extensive twentieth-century records, the extraordinarily informative **Donggwoldo / Donggwoldo-hyeong** tradition, and an unusually large body of building-specific repair reports.

### Nakseonjae, Seokbokheon and Sugangjae: the best domestic comparison set

If I were selecting **one report to ingest in full first**, it would be:

**`창덕궁 낙선재 일곽 : 정밀실측조사보고서` — Cultural Heritage Administration, 2016.**

The report is **1,068 pages** and includes a CD; the National Assembly Library provides electronic access information. It independently surveys Nakseonjae, Seokbokheon and Sugangjae and then documents subsidiary buildings and the surrounding precinct. citeturn16search0

For **each of the three main buildings**, the report has separate sections for:

- plan,
- platform and stairs,
- base stones,
- columns,
- upper framing,
- eaves,
- roof,
- windows/doors,
- architectural fittings/finishes,
- and additional details.

Nakseonjae additionally has an explicit bracket section. citeturn16search0

For your eventual reusable architectural corpus, its tables are unusually valuable. They include full and individual **bay measurements**, platform dimensions and heights, column measurements, high-column measurements, purlins and horizontal members, plus detailed measurements of different floor constructions. The drawings include column details, beams, secondary beams, struts, rafter/eave geometry, ridge and gable details, window-location drawings, **merum**, **umulmaru** floor details, railings and subsidiary buildings. citeturn16search0

Equally importantly, it contains historical comparison material: pre-restoration and post-restoration plans, early-twentieth-century precinct plans and a chronology of alterations. Thus one report can tell your later agents both “what is there” and “which parts belong to which intervention.” citeturn16search0

Nakseonjae is therefore much more valuable to your project than its decorative reputation might suggest. It is a measured catalogue of a **residential palace architectural family**, with three related buildings surveyed under the same methodology.

### Injeongjeon and Injeongmun

For Injeongjeon, locate:

**`창덕궁 인정전 실측조사보고서` — Cultural Property Administration, 1998.**

The report is repeatedly used as primary measurement evidence in later architectural-history scholarship, including research on the geometry of Donggwoldo. citeturn19search6turn19search1

The current KHS record identifies Injeongjeon as the 1804 rebuilding and describes its frame as multi-cluster bracket construction with a two-high-column/seven-purlin configuration. citeturn18search6

But the current structure and courtyard must not be interpreted without the 1908 transformation evidence. The paper already in your Drive—

**Woo Don-Son & Kee Sehwang, “A Study on the Remodeling of Injeongjeon Area at Changdeokgung Palace in 1908”**

—uses historical plans and identifies a major remodelling campaign. It also points to one of the richest historical-plan resources in this whole project: the Academy of Korean Studies/Jangseogak's **`근대건축도면집` (Collection of Modern Architectural Drawings)**. The authors state that the published set contains 174 drawings, 122 concerning palaces, of which **101 relate to Changdeokgung**. fileciteturn2file0L2-L2

For Injeongmun, locate:

**`창덕궁 인정문 : 정밀실측조사보고서` — Cultural Heritage Administration, 2010.**

The KHS Digital Service has a substantial associated digital record set, including 3D views of all sides, interior framing views and scan-derived/detail records of horizontal structural members. citeturn18search5turn18search12

Together, Injeongjeon + Injeongmun are a useful paired corpus for studying the differences between a major ceremonial hall and its principal gate without leaving the same precinct.

### Seonjeongjeon

Your Drive already contains one of the most useful interpretive papers for this building:

**Lee Jong-Seo, “The Architectural Structure of Seonjeong-jeon in Changdeok Palace as a Ceremonial Hall,” Journal of Architectural History 29(2), 2020.**

The important point for your modelling research is that the paper explicitly argues that several elements seen in the current building are **not faithful representations of the historically documented configuration**. It reconstructs the original front as three door openings—central royal access plus side doors—rather than the present side-window arrangement, and argues that the interior previously used square brick flooring rather than the wooden floor now seen. fileciteturn1file0L2-L2

It also describes Seonjeongjeon as a three-bay by three-bay building with two interior high columns dividing the interior spatially. fileciteturn1file0L2-L2

This makes Seonjeongjeon a particularly useful example of why the corpus should contain an explicit **“source date / architectural state”** field. Current photographs alone would encode the 1999 restoration choice rather than the configuration that Lee reconstructs from documentary evidence. fileciteturn1file0L2-L2

### Daejojeon, Huijeongdang and the inner palace

The Heritage Portal URL you supplied is a record for **Changdeokgung Daejojeon** rather than a general palace-data page. The portal-level record is useful for identification, but for architectural reconstruction the relevant material is the deeper survey, repair and historical literature. citeturn4view0

The crucial source already in your Drive is:

**Woo Don-Son & Kee Se-Hwang, “A Study on Reconstruction of Naejeon Area at Changdeokgung Palace in 1920.”**

Its significance is difficult to overstate for a 3D project. After the 1917 fire, the Daejojeon/Huijeongdang area was reconstructed in a form that deliberately retained a traditional-looking exterior—using materials originating in Gyeongbokgung—while introducing modern and foreign-derived interior construction, including Western-style standing furniture/heating arrangements and Japanese-influenced corridor, veranda and storage configurations. fileciteturn3file0L2-L2

In other words, **Daejojeon/Huijeongdang is a dangerous building family from which to infer generic Joseon interior modules without period filtering**.

The report corpus to acquire here includes:

**`창덕궁 희정당 수리보고서` — 2002**  
**`창덕궁 희정당 신관 실측·수리보고서` — 2003**  
**`창덕궁 경훈각 실측·수리보고서` — 2004**  
**`창덕궁 함원전 보수공사` — 2005**  
**`창덕궁 대조전 침대 복원보고서` — 2009**  
and the newer **`창덕궁 대조전 및 희정당 관람환경 개선공사 수리보고서 (건축, 2차)` — 2023**. citeturn19search0turn19search4turn19search9

These reports should let your later corpus distinguish original traditional timber geometry, transferred material, twentieth-century intervention and present visitor presentation much more reliably than the current building alone.

### Donhwamun, Juhamnu and other discrete structures

Changdeokgung has an unusually broad building-specific report literature. An AKS/Hanyang bibliography collates the following particularly relevant titles: citeturn19search0turn19search2

| Building/precinct | High-value report |
|---|---|
| Injeongjeon | `창덕궁 인정전 실측조사보고서` |
| Injeongmun | `창덕궁 인정문 정밀실측조사보고서` |
| Juhamnu | `창덕궁 주합루 정밀실측보고서` |
| Gyeonghungak | `창덕궁 경훈각 실측수리보고서` |
| Uirojeon | `창덕궁 의로전 실측수리보고서` |
| Seunghwaru precinct | `창덕궁 승화루 및 일곽 실측수리보고서` |
| Buyongjeong | `창덕궁 부용정 부용지 실측조사보고서`; `창덕궁 부용정 해체실측 수리보고서` |
| Palace pavilions | `창덕궁 정자(상량정, 태극정, 능허정) 실측수리보고서` |
| Chwijeong | `창덕궁 취운정 해체 보수공사 수리보고서` |
| Uiduhap | `창덕궁 의두합 권역 보수공사 수리보고서` |
| Old Seonwonjeon | `창덕궁 구선원전 실측조사보고서` plus the later precinct reconstruction report |
| Huijeongdang | `창덕궁 희정당 수리보고서`; `창덕궁 희정당 신관 실측수리보고서` |

The **Juhamnu** Digital Service data is also notable because the current project records include 3D-derived north/south/east/west elevations and an **internal structural view**, not only exterior photography. citeturn17search3

For Donhwamun, KHS likewise has digital plan/elevation documentation; early photographic documentation is additionally present in Sekino Tadashi's early-twentieth-century survey corpus. citeturn18search3

## Historical controls: plans, photographs and construction records

Measured surveys tell you accurately what was measured; they do not automatically tell you **which historical moment you are measuring**. This is the single largest historical-risk issue in the project.

### Bukgwoldo-hyeong for Gyeongbokgung

As noted above, `북궐도형` is indispensable because it preserves the late-nineteenth-century arrangement of a much fuller Gyeongbokgung than survives today and annotates architectural information down to bay/column information. citeturn21search0

It should be supplemented with `경복궁배치도`, `경복궁고도`, `궁궐지`, and restoration/excavation documents. Comparing the older plans is important because the layout itself changed during the late nineteenth century; the literature documents instances where buildings switched positions or changed connecting corridors between successive plan sources. citeturn21search6turn21search8

### Donggwoldo and Donggwoldo-hyeong for Changdeokgung

For Changdeokgung, the analogous family is **`동궐도 (東闕圖)`**, **`동궐도형 (東闕圖形)`** and later measured/colonial plans.

Donggwoldo is exceptionally valuable for topology and architecture that has disappeared, but it is a pictorial axonometric representation rather than a modern dimensioned plan. A dedicated research paper has investigated whether it can be geometrically transformed into plan information and cross-checked its reconstruction against sources including the colonial-period `창덕궁평면도`, the 1998 Injeongjeon measured survey, the 2016 Juhamnu survey and the Donhwamun structural report. citeturn19search6

That paper is worth adding to the corpus precisely because it addresses your problem of turning a historical representation into spatially consistent information:

**`러버쉬팅변환을 통한 「동궐도(東闕圖)」의 평면도 제작 가능성 연구`**. citeturn19search6

For lost or altered Changdeokgung buildings, I would never ingest Donggwoldo geometry without also keeping the corresponding `동궐도형`, later `창덕궁평면도`, measured-survey control points and historical photography.

### Jangseogak's modern architectural drawings

The Jangseogak/Academy of Korean Studies publication:

**`근대건축도면집` (도면편 / 해설편), 2009**

deserves its own ingestion project. The Changdeokgung-remodelling research in your Drive reports that **101 drawings in the collection concern Changdeokgung**. These include documents produced during a period when buildings were being altered, repurposed and partially removed, which makes them especially powerful for comparing pre-change, planned-change and post-change states. fileciteturn2file0L2-L2

A specifically important item to look for is the colonial-period **`창덕궁평면도 (昌德宮平面圖)`**, identified in later architectural research as a Jangseogak holding. citeturn19search6

### Early systematic photographic surveys

KHS has digitized Sekino Tadashi's **`한국건축조사보고`**, published in 1904 following his 1902 field survey. It contained 363 plates and includes records for Gyeongbokgung's Gyeonghoeru, Geunjeongjeon/Geunjeongmun and Hyangwonjeong, as well as Changdeokgung's Geumcheongyo, Nakseonjae, Donhwamun, Seonjeongjeon, Injeongmun, Injeongjeon and Juhamnu. citeturn12search8turn12search11

The related **`조선고적도보`** photographic/illustrative corpus should likewise be treated as a major historical-control source. It is specifically cited in architectural scholarship reconstructing Gyeongbokgung buildings such as Gangnyeongjeon. citeturn20search3turn21search11

For modelling, old photographs are often surprisingly important even when no dimensions are marked: once a façade is anchored by measured bay dimensions, photographs can resolve **door leaf counts, lower merum arrangements, wall-versus-opening locations, railings, platform edges, corridor attachment and elements subsequently removed**.

### Uigwe and construction records

The Uigwe are not substitutes for measured surveys, but they become very valuable when determining **original construction logic, member names, material quantities, rebuilding phases and lost architectural features**.

Your Seonjeongjeon paper explicitly makes use of Kyujanggak's original Uigwe records, including the 1608 ceremonial documentation, while the Daejojeon/Huijeongdang study points to `창덕궁수리도감의궤` and `창덕궁영건도감의궤`. fileciteturn1file0L2-L2 fileciteturn3file0L2-L2

Relevant titles to collect include:

`창덕궁수리도감의궤`  
`창덕궁영건도감의궤`  
`인정전영건도감의궤`  
`인정전중수도감의궤`

and, for other comparative palace construction, the broader series of **영건의궤**. Research into architectural terminology has explicitly cross-referenced the Injeongjeon survey with these Uigwe when interpreting bracket and framing terms. citeturn19search7

For Gyeongbokgung, **`경복궁영건일기`** should likewise be part of the historical construction corpus. It appears in the AKS inventory of core reconstruction sources. citeturn20search0

## Architectural research that fills the gaps between drawings

The raw measurements should form the corpus backbone, but several research topics are worth adding because they explain components that are either hidden in survey drawings or easily misclassified.

### Spatial evolution and building function

For overall Changdeokgung development, locate:

**Cho Jae-mo, `昌德宮 成長 過程과 配置 特性에 관한 연구`, Seoul National University dissertation, 1997.**

Later Changdeokgung research continues to cite it as a foundational study of the palace's growth and spatial configuration. citeturn19search1

Also important is:

**Park Hee-yong et al., `창덕궁 인정전 일곽의 공간구성 변화`, 2005.**

This is useful for separating architectural form from precinct evolution. citeturn19search1

For Gyeongbokgung:

**Lee Hye-won, `경복궁 중건이후 전각구성의 변화 — 「경복궁배치도」와 「북궐도형」을 중심으로`, doctoral dissertation, 2008**

is repeatedly cited in the building-specific historical literature because it directly compares the two crucial late-nineteenth-century plan sources. citeturn21search3turn21search11

For broader palace architecture:

**Cho Jae-mo, `조선시대 궁궐의 의례운영과 건축형식`, Seoul National University doctoral dissertation, 2003**

is worth retaining even though ceremonial interpretation is not your primary interest. Its value here is that palace functions frequently explain otherwise puzzling differences in plan, access and room/opening organization. citeturn21search3

### Foundations and archaeological evidence

For demolished buildings, the plan visible above ground—or in a historical drawing—is often not enough to establish the actual column grid or floor construction. A useful comparative study is:

**Choi In-hwa, `조선시대 5대 궁궐 건물지 기초의 고고학적 연구` / “An Archaeological Study on the Foundations of Five Palaces of the Joseon Period,” Heritage: History & Science 54(1), 2021.**

It analyzes palace building foundations archaeologically, making it a useful interpretive companion to the numerous Gyeongbokgung excavation reports. citeturn15search10

For restored Gyeongbokgung precincts such as the East Palace, kitchens, Heungbokjeon and Taewonjeon, **archaeological reports should be ingested alongside the reconstruction report rather than after it**. The AKS source inventory identifies dedicated excavation reports for these areas. citeturn20search0

### Floors, ondol and ceilings

These elements are particularly relevant because they affect visible interior volume and because the interior of a traditional timber shell cannot safely be inferred from exterior bays.

A recent doctoral study directly on your two target palaces is:

**Lim Jun-gu, `조선시대 궁궐 온돌의 문화유산적 가치와 교육적 활용 가능성 연구 : 경복궁과 창덕궁 전각의 온돌을 중심으로`, Korea National University of Heritage, 2025.**

It explicitly studies the structural characteristics and traditional technology of palace ondol in Gyeongbokgung and Changdeokgung. citeturn15search9

For ceilings:

**Lee Jong-Seo, `조선시대 궁궐건축의 우물천장 구조 종이반자 연구` / “Research on Paper Board Banja With Woomul Structure of Royal Palaces in the Joseon Dynasty,” Journal of Architectural History 32(1), 2023**

is useful for distinguishing different ceiling constructions that can otherwise look superficially similar in photographs. citeturn15search3

And again, the Nakseonjae report is unusually good here because its measured drawings explicitly include several **umulmaru floor assemblies** and observed ceiling/floor conditions rather than merely noting room finish types. citeturn16search0

### Geometric reconstruction from historical drawings

For Changdeokgung:

**`러버쉬팅변환을 통한 「동궐도」의 평면도 제작 가능성 연구`**

is directly relevant to using Donggwoldo computationally and cross-validating it against measured evidence. citeturn19search6

A further doctoral dissertation worth collecting is:

**Lee Jae-yong, `조선 후기 동궐(창덕궁·창경궁)의 원형 추정에 관한 연구 — <동궐도>의 기하학적 재구성을 통하여`, Korea National University of Cultural Heritage, 2019.**

The AKS bibliography specifically identifies it as a study of reconstructing the late-Joseon East Palace through geometric reconstruction of Donggwoldo. citeturn19search8

Those works are more relevant to your future data analysis than generic art-historical studies of Donggwoldo because they explicitly interrogate its spatial geometry.

## Recommended corpus manifest

The table below is the collection I would hand to the agents before attempting any architectural generalization. “First” means the material is likely to return direct geometry useful across multiple buildings; “Second” means it is crucial for historical state or specific building families; “Reference” is interpretive/contextual.

| Priority | Corpus item | Why it belongs in the dataset |
|---|---|---|
| **First** | **KHS Digital Service: all Gyeongbokgung and Changdeokgung records filtered to `도면`, `3D`, `보고서`** | Central official source for original DWG/report/scan material; supports source-file requests. citeturn17search0turn17search1 |
| **First** | **`경복궁 사정전 일곽 : 정밀실측조사보고서` (2014)** | 727 pages; numerical bay, platform, base-stone, column, beam and roof measurements; 3D scans and measured drawings. citeturn13search1 |
| **First** | **Raw Sajeongjeon/Cheonchujeon KHS DWGs** | Direct CAD drawings including plans, sections, elevations, roof/eave and component details; project contains 865 records. citeturn12search2turn12search4turn12search5 |
| **First** | **Geunjeongjeon KHS measured drawing family** | Component-level drawings for columns, brackets, framing, doors/windows, eave geometry and platform details. citeturn5search0turn5search3turn5search4turn5search10 |
| **First** | **`창덕궁 낙선재 일곽 : 정밀실측조사보고서` (2016)** | Probably the richest reusable domestic-building corpus: three related main buildings, subsidiary buildings, windows, floors, columns, beams, room layouts and historical states. citeturn16search0 |
| **First** | **`창덕궁 인정전 실측조사보고서` (1998)** | Core measured source for a major Changdeokgung ceremonial hall and a control geometry used by later researchers. citeturn19search6 |
| **First** | **`창덕궁 인정문 정밀실측조사보고서` (2010) + KHS 3D records** | Detailed gate corpus, including internal framing and multi-view 3D-derived drawings. citeturn18search5turn18search12 |
| **First** | **`창덕궁 주합루 정밀실측보고서` (2016)** | Important two-storey pavilion/library case; associated digital records include interior structure. citeturn19search0turn17search3 |
| **First** | **`창덕궁 경훈각 실측수리보고서` (2004)** | Inner-palace building with measured + repair evidence. citeturn19search0 |
| **First** | **`창덕궁 희정당 수리보고서` (2002)** | Critical evidence for structure and twentieth-century transformations. citeturn19search0 |
| **First** | **`창덕궁 희정당 신관 실측·수리보고서` (2003)** | Measured repair record available through National Archives. citeturn19search9 |
| **First** | **`창덕궁 승화루 및 일곽 실측수리보고서` (2005)** | Adds a different residential/library precinct and subsidiary architecture. citeturn19search0 |
| **First** | **`창덕궁 의로전 실측수리보고서` (2004)** | Additional measured palace-hall type useful for comparative corpus work. citeturn19search5 |
| **Second** | **`북궐도형`** | Essential late-nineteenth-century Gyeongbokgung layout; contains room labels, bay data, column spacing/height and bracket annotations. citeturn21search0turn21search1 |
| **Second** | **`경복궁배치도` + `경복궁고도`** | Comparative plan states for identifying change rather than assuming Bukgwoldo-hyeong is timeless. citeturn21search3 |
| **Second** | **`동궐도` + `동궐도형`** | Main historical spatial evidence for Changdeokgung/Changgyeonggung, particularly vanished structures and connections. citeturn19search6 |
| **Second** | **Jangseogak `근대건축도면집` (2009)** | Extremely rich early-twentieth-century plan archive; the cited study reports 101 Changdeokgung drawings. fileciteturn2file0L2-L2 |
| **Second** | **Colonial-period `창덕궁평면도`** | Orthographic plan control between historical Donggwoldo and modern surveys. citeturn19search6 |
| **Second** | **Sekino, `한국건축조사보고` (1904)** | Early systematic visual record of multiple target buildings at both palaces. citeturn12search8turn12search11 |
| **Second** | **`조선고적도보` palace volumes** | Early photographs/drawings useful for pre-restoration openings, corridors and exterior details. citeturn20search3turn21search11 |
| **Second** | **`경복궁 복원기본계획` and 1995 restoration plan** | Establishes evidence and decisions behind reconstructed Gyeongbokgung buildings. citeturn20search0turn20search1 |
| **Second** | **`경복궁 동궁지역 중건공사보고서`** | Reconstruction evidence for Jaseondang/Bihyeongak precinct. citeturn20search1 |
| **Second** | **`경복궁 소주방권역 중건보고서` + excavation report** | Smaller service architecture, corridors and archaeological plans—valuable counterweight to major halls. citeturn20search0 |
| **Second** | **`경복궁 태원전 권역 중건보고서` + excavation material** | Large reconstructed precinct with underlying archaeological evidence. citeturn20search0 |
| **Second** | **`경복궁 함화당·집경당 권역 보수복원공사 보고서`** | Residential/subsidiary architecture and reconstructed connections. citeturn20search0 |
| **Second** | **`경복궁 자경전 및 자경전 십장생굴뚝 정밀실측조사보고서` (2010)** | Measured royal residential precinct material; official KHS survey. citeturn12search0turn12search1 |
| **Second** | **`경복궁 근정전 월대 보수공사 수리보고서` (2023)** | Detailed dimensions and historical analysis of Geunjeongjeon's platform, including construction-unit analysis. citeturn13search0 |
| **Second** | **`창덕궁 구선원전 실측조사보고서` + precinct restoration report** | Measured structure plus reconstruction documentation. citeturn19search5 |
| **Second** | **`창덕궁 부용정 해체실측 수리보고서`** | Disassembly reports can reveal member geometry and joints inaccessible in ordinary surveys. citeturn19search0 |
| **Second** | **`창덕궁 정자(상량정·태극정·능허정) 실측수리보고서`** | Compact pavilion variants—a useful comparison group distinct from large rectangular halls. citeturn19search0 |
| **Reference** | **Lee Jong-Seo, Seonjeongjeon, 2020** | Essential correction of current door/floor configuration when selecting historical state. fileciteturn1file0L2-L2 |
| **Reference** | **Woo & Kee, Injeongjeon remodelling, 2014** | Documents 1908 alterations and directs you to Jangseogak's plan archive. fileciteturn2file0L2-L2 |
| **Reference** | **Woo & Kee, Naejeon reconstruction, 2014** | Essential warning against interpreting 1920 Daejojeon/Huijeongdang as an untouched traditional interior. fileciteturn3file0L2-L2 |
| **Reference** | **Lee Hye-won, Gyeongbokgung post-reconstruction spatial change** | Systematic comparison of Bukgwoldo-hyeong and Gyeongbokgung Baechido. citeturn21search3 |
| **Reference** | **Cho Jae-mo, palace ritual operation and architectural form** | Broad architectural typology and spatial-function interpretation. citeturn21search3 |
| **Reference** | **Donggwoldo rubber-sheet transformation study** | Explicit methodology for deriving and checking plan geometry from Donggwoldo. citeturn19search6 |
| **Reference** | **Lee Jae-yong, geometric reconstruction of Donggwol, 2019** | Dedicated geometric reconstruction research for Changdeokgung/Changgyeonggung. citeturn19search8 |
| **Reference** | **Lim Jun-gu, palace ondol study, 2025** | Directly compares ondol in Gyeongbokgung and Changdeokgung. citeturn15search9 |
| **Reference** | **Lee Jong-Seo, palace ceiling construction, 2023** | Useful evidence for interior ceiling assemblies. citeturn15search3 |
| **Reference** | **Choi In-hwa, archaeological study of five-palace foundations, 2021** | Interprets building-site foundations and archaeological evidence across the palace corpus. citeturn15search10 |

The material already in your Drive can therefore be sorted more sharply. The **Seonjeongjeon**, **1908 Injeongjeon**, and **1920 Naejeon** papers are high priority because they resolve historical-state problems. The garden, pigment and feng-shui papers are legitimate scholarship but low priority for the particular architectural corpus you are building. The two newly added Changgyeonggung restoration-planning reports could still become useful later as a **comparative palace dataset**, especially once you begin asking whether a component family seen at Gyeongbokgung or Changdeokgung generalizes across late-Joseon palace architecture.

The key strategic finding from the research is therefore that you do **not** need to derive most basic palace geometry from photographs or approximate drawings. For a meaningful subset of the buildings, the state has already produced the underlying measurements, CAD details, 3D scans and disassembly documentation. The historical-research problem is instead to connect those highly accurate records to the **correct historical state**—and to avoid allowing an accurate survey of a restored or twentieth-century-modified building to masquerade as an untouched Joseon prototype. The combination of KHS measured-survey material, Bukgwoldo-hyeong/Donggwoldo-family historical plans, Jangseogak architectural drawings, repair reports and the change-over-time scholarship in your existing folder provides a strong enough source base to build that distinction explicitly. citeturn17search1turn21search0turn19search6