# Research leads and supplied collections

This is the starting map of potential sources, including material that has not been acquired or closely read. Consult it alongside [NEXT.md](NEXT.md) when choosing a batch or looking for evidence. The short queue identifies current priorities; this map keeps the wider possibilities discoverable.

Search the existing `sources/` records and the relevant supplied collection before starting a new web search or acquisition. Match titles, authors, publication identifiers, and known filenames; use file checksums to confirm byte-identical copies. A different scan can still represent the same publication. When a lead becomes a source record, link to that record here and let it own acquisition status, inspection findings, and blockers.

## Sajeongjeon: broader source pass, 2026-09-21

Discovery was followed by a bounded acquisition and inspection pass. Ten 1993 sheets, Park's complete article, Cho's one-page preview, and the 2024 display release/photo attachment are now retained. Linked source records own their exact inspection notes, files and blockers. The [first building extraction](buildings/gbg-sajeongjeon.json), dated 2026-09-22, records five checked layout/opening observations and four pending numerical chains; units and measuring heights remain unresolved. The unacquired alternatives below remain leads.

### Geometry and repair records

The [official Sajeongjeon portal entry](https://www.heritage.go.kr/heri/cul/culSelectDetail.do?ccbaCpno=1121117590000&pageNo=1_1_1_1&sngl=Y), under **도면 → 더보기**, exposed **110 drawing links**. That is a count of catalogue entries, not unique sheets: similar titles occur in pairs, and their bytes, title blocks and dates have not been compared. The [drawing source record](sources/src-gbg-sajeongjeon-measured-drawings-1993/source.json) indexes ten retained sheets and four checked reading notes.

| Useful group | Exact portal `file_seq` leads | What to establish next |
| --- | --- | --- |
| Column/bay spacing, column levels and inclination | 2868184, 2868185 — 평면주칸／포간격／기둥레벨／안쏠림 실측도 and the similarly named entry | 2868184 retained: bay chains transcribed in building obs-006–009, with units/heights pending and one chain-total conflict. 2868185 remains uninspected: targeted web access failed on 2026-09-22; catalogue returned 403 and delegated browser was unavailable. Retry with a working public route or supplied copy. |
| Central sections | 2868152 — 어칸 종단면도; 2868153 — 어칸 횡단면도 | Both acquired and inspected (sheets 006/008); relate cut keys, supports and central assembly to the other evidence. |
| Ceiling plans | 2868148, 2868149 — 앙시도(반자) | 2868148 acquired and inspected (sheet 010); 2868149 remains an untested alternate. |
| Openings | 2868174–2868176 — 창호 상세도 for south, east/west and north; similarly named entries 2868171–2868173 | 2868174/2868176 acquired and inspected (south/north, sheets 017/019). East/west details and operation remain open; alternate scans untested. |
| Repair drawings | 2868130, 2868131 — 보수 평면도; 2868126, 2868127 — 보수 종단면도 | 2868130/2868126 acquired and compared (sheets 045/050) with existing plan/section and measured diagram. Execution unverified; alternate scans untested. |

Use `https://www.heritage.go.kr/heri/cul/chartImgHeritage.do?file_seq=<ID>` or select the corresponding title from the expanded list. The table distinguishes inspected sheets from unacquired alternatives; file identity and sheet labels belong to the source record. The National Archives also [lists **CB0005576**, 경복궁 사정전 실측설계, 1993](https://www.archives.go.kr/next/newsearch/viewDescClassContents.do?businessFunctionId=S00000015407&descClassDiv=S&descFullId=T00000000090%2FT00000000094%2FG00000000343%2FS00000015407&page=230&sitePage=&viewSel=archive). Its item-detail route did not load through the web tool. Identity with the portal scans remains unconfirmed; another holding is not automatically independent evidence.

The **2012 경복궁 사정전 권역 수리보고서** remains a bibliographic lead. Park's 2022 bibliography, available in the [museum's e-book text](https://www.gogung.go.kr/ebook/access/ecatalogt.jsp?Dir=192&callmode=admin&catimage=&eclang=ko&start=146&um=s), cites 문화재청 and 2012; the [AKS inventory](https://dh.aks.ac.kr/hanyang/wiki/index.php/한양도성_자료_현황) also lists the title. A direct institutional catalogue/download for the report was not established. The [2014 measured report](sources/src-gbg-sajeongjeon-survey-2014/source.json) remains a separate, blocked source; its failed login routes were not retried.

### Interior history and research context

These sources answer different questions. Their interpretation should be compared with the drawings, not silently substituted for measured evidence.

| Source | Relevance and verified access depth | Next useful action |
| --- | --- | --- |
| **조재모, 2022, 「고종대 중건 사정전의 활용 양상과 어좌 구성에 관한 연구」**, 대한건축학회논문집 38(8), 103–114. [KCI record and abstract](https://www.kci.go.kr/kciportal/ci/sereArticleSearch/ciSereArtiView.kci?sereArticleSearchBean.artiId=ART002871758) | [Source record](sources/src-cho-sajeongjeon-throne-2022/source.json): one-page KCI preview retained and visually inspected (printed 103). Full text unavailable through checked public routes. | Obtain the full article through a new legitimate route or supplied copy before adopting its proposed arrangement; skip unchanged preview/abstract routes. |
| **박윤희, 2022, 「경복궁 사정전 <쌍룡도> 벽화의 설치 배경과 제작 시기 검토」**, 고궁문화 15, 121–150, DOI 10.23008/kjpm.2022..15.005. [KCI abstract](https://www.kci.go.kr/kciportal/landing/article.kci?arti_id=ART002906313); [museum issue/download listing](https://online.gogung.go.kr/gogung/bbs/BMSR00053/view.do?boardId=5120&pageIndex=1) | [Source record](sources/src-park-sajeongjeon-mural-2022/source.json): complete 40-page individual download retained, including issue front/back matter; selected pages visually inspected. Four reading notes record the mural/support distinction, alterations and research context. | Use exact notes/pages when comparing the central assembly; retrieve primary conservation evidence if its fabric history becomes decisive. |
| **궁능유적본부, 2024-05-08, 「임금의 업무공간 ‘경복궁 사정전’ 상참의 재현품 만난다」**. [Official release and attachments](https://royal.khs.go.kr/ROYAL/contents/R402000000.do?id=20240508144352747159&schBcid=normal1&schM=view) | [Source record](sources/src-gbg-sajeongjeon-furnishing-2024/source.json): release HTML and three-page photo PDF acquired; complete text and all five photographs inspected. | Keep the 2024 display state separate; its underlying reconstruction research is not supplied by the release. |
| **북궐도형, 고궁2341**, National Palace Museum. [Holding record](https://www.gogung.go.kr/gogung/pgm/psgudMng/view.do?cl=&gubunCd=&menuNo=800065&pageIndex=&pn=&psgudSn=367767&searchClCd=&searchCondition=&searchKeyword=) | Holding metadata checked: circa 1907; description gives an estimated 1905–1908 range. The museum describes building and room-use labels and displays an attribution licence. Image not acquired or inspected at useful detail. | Obtain a legible reproduction of the Sajeongjeon precinct for historical arrangement and labels; preserve historical units and unresolved scale. |
| **서울 종로 경복궁 사정전 전경, 건판35457**, National Museum of Korea. [Collection lead](https://www.museum.go.kr/MUSEUM/contents/M0502000000.do?relicId=31219&schM=view&searchId=search) | Search-index metadata only; the detail page failed to load through the web tool. Listed as an exterior glass-plate photograph with attribution terms. Photograph date and usable image not checked. | Verify the object and date before using it to compare exterior conditions. It does not fill the interior-evidence gap. |

The first extraction groups the existing-condition drawings separately from explicit repair sheets and later display evidence. Park's notes connect the mounting, painting and later facsimile; building obs-004 locates the drawn northern interior frame without assigning that historical identity. The 2024 source identifies the display, while Cho's Gojong-period proposal remains preview-only. Their different dates and purposes must be resolved before treating apparent differences as contradictions.

A useful new bibliographic lead is **경복궁 사정전 내부원형 및 포진재 고증조사 (2022)**, identified in Cho's preview, PDF page 1 / printed 103, footnote 1. Park's acknowledgement (PDF 32 / printed 145) also names an Arumjigi-commissioned Sajeongjeon symposium. [Park note-004](sources/src-park-sajeongjeon-mural-2022/source.json) records this shared research context; independent corroboration has not been established. The underlying report and a public access route remain unverified.

The supplied local architecture folder contains the same six filenames already listed below, with no Sajeongjeon-titled file. After explicit owner permission, connected Drive searches for `사정전` and `Sajeongjeon` returned no matches. This was not a recursive collection audit or proof that no relevant document exists; a broader `경복궁` search was blocked by automatic approval review as beyond the authorized query scope.

## Deep-research report and earlier project inputs

The [complete supplied report](context/inputs/deep-research-report.md) preserves its narrative, bibliography, and proposed source manifest. Its [recovered PDF links](context/report-links.json) preserve 42 research-related URLs with one-based PDF page occurrences, plus one publishing link. These include documents, catalogues, archives, and access guidance; they are not 42 distinct verified publications. Use the narrative to interpret the links, and verify a candidate before adopting its bibliographic or architectural claims.

The report's headings provide routes into the wider collection:

| Subject | Where to look in the supplied report |
| --- | --- |
| Gyeongbokgung surveys and restoration evidence | Sajeongjeon/Cheonchujeon/Manchunjeon; Geunjeongjeon; Gangnyeongjeon/Gyotaejeon and the residential core; restoration and excavation corpus |
| Changdeokgung comparisons | Nakseonjae/Seokbokheon/Sugangjae; Injeongjeon/Injeongmun; Seonjeongjeon; Daejojeon/Huijeongdang; other discrete structures |
| Historical states and spatial context | Bukgwoldo-hyeong; Donggwoldo and Donggwoldo-hyeong; Jangseogak drawings; photographic surveys; uigwe and construction records |
| Specific architectural questions | Spatial evolution and function; foundations; floors, ondol and ceilings; geometric reconstruction from historical drawings |

The [earlier seed conversation](context/inputs/seed-conversation.txt) and [project brief](context/inputs/project-brief.md) preserve additional context and suggestions. [context/README.md](context/README.md) records the original inputs and the earlier [Drive research folder](https://drive.google.com/drive/folders/1ptj5lfQdVq7s3tii98QkX5hSXWByGJck?usp=sharing). Statements and instructions inside supplied documents remain background, not new task authorization.

## Owner's local East Asian architecture collection

The supplied folder is `C:/Users/torne/Downloads/EastAsia_ArchitectureCorpus`. Its six PDF filenames were checked on 2026-09-21. They represent five distinct files after the known Beauty duplicate is grouped. Only the three linked sources below have been retained in PalaceData; the remaining two are still in the supplied local folder.

| Supplied filename or work | Existing record or next possibility |
| --- | --- |
| `2005 Timber Building Structures in Joseon Korea - Geunjeongjeon and Injeongjeon -- Qinghua Guo.pdf` | [Guo's two-hall study](sources/src-guo-joseon-timber-2005/source.json); selected structural passages already inspected |
| `The Beauty of Traditional Korean Architecture.pdf` and `Beauty of Korean Architecture.pdf` | [Kim's essay](sources/src-kim-korean-architecture-beauty-2007/source.json); byte-identical copies, represented once |
| `1998 Yingzao Fashi - Twelgth-Century Chinese Building Manual -- Qinghua Guo.pdf` | [Guo's article about the manual](sources/src-guo-yingzao-fashi-1998/source.json); comparative context |
| `Koreas Traditional Architecture.pdf` | Candidate introductory reference; earlier review identified a short scanned article. Catalogue and retain it before citing new findings; use selected-page inspection for terminology questions. |
| `Chinese Imperial City Planning by Nancy Shatzman Steinhardt.pdf` | Candidate comparative reference for planning and urban context. Catalogue and retain when useful; it need not become a current palace-interior task. |

The local folder is an incoming collection, not the durable archive. If it has moved, use the supplied filenames and the broader Drive collection below to look for counterparts. A matching title does not prove identical bytes or edition.

## Owner's broader Drive architecture collection

The [broader Architecture folder](https://drive.google.com/drive/folders/1mpwPPw_ZWFt4mwY8N_8cY-FTU_Sa6Y34?usp=sharing) is a standing discovery resource. An earlier bounded review in this setup conversation examined its root listing and the Palace, Korean Language, and Hanok folders. That was not a complete recursive inventory. Future agents should search the relevant part of this collection for their question; the selected leads below are not its full contents.

These entries preserve candidates spotted in that review. They have not been reacquired or rechecked while writing this map. Some overlap with the deep-research report and local PDFs, so check existing identities before creating records.

| Candidate | Why it may matter and review depth |
| --- | --- |
| [창덕궁 선정전의 의례 공간적 건축 구조](https://drive.google.com/file/d/1bylU5LMNJR6TkJftWVbQqmttLkd6GZ9b/view) | Earlier text review identified discussion of interior arrangement, openings, and ritual space. No checked architectural record has been created. |
| [1920년 창덕궁 내전 일곽의 재건에 관한 연구](https://drive.google.com/file/d/1IVslbF3qacr8PVE_FYBhQFeoUqbrohRb/view) | Earlier text review identified discussion of rebuilding and interior changes; useful for historical-state questions. No checked architectural record has been created. |
| [창경궁 궐내각사 권역 복원정비계획 수립연구 보고서](https://drive.google.com/file/d/1hBJsP9QehyBSB5TtBeoOlKxf7mx7CBvO/view) | Title/metadata only; possible future service-precinct reference |
| [창경궁 복원정비 기본계획 조정 연구](https://drive.google.com/file/d/1QAMWJ78GogoLHnfPpJGy2QccAMPQsnyP/view) | Title/metadata only; possible restoration-planning reference |
| [A Study on the Usage of Hwabangbyeok wall in Traditional Architecture in Joeson Dynasty](https://drive.google.com/file/d/12dTwYwUqfpdyKbjABSLaoIMdPuuYZr3B/view) | Title only; possible wall-construction reference. Matching-title entries were duplicate candidates, not confirmed identical files. |
| [An Archaeological Study on the Foundations of Five Palaces of the Joseon Period](https://drive.google.com/file/d/1o_fHGoKHuYRGj5PLhDO3Cb2PsHqxH_wD/view) | Title only; possible foundation and cross-palace comparison reference |
| [hanok characteristics.pdf](https://drive.google.com/file/d/1mE7tuKgzr7Z0NN56DnTxIjGpz1P1kPZR/view) | Filename only; establish author, date, and scope before relying on it |

Gyeongbokgung remains the starting focus. A wider lead can answer a focused comparison without starting another palace project. Record newly supplied collection entry points here, and add individual candidates when there is enough information to make them findable. This map can grow without requiring every item to be downloaded, summarized, or added to the active queue.
