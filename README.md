# 책 출간의 역사 · A History of Book Publishing

필사본에서 전자책까지, 한 해에 책이 몇 종 나왔는지를 세는 방법과 함께 보는 역사 사이트입니다. 출처마다 선을 따로 긋고, 출처가 스스로 셈법을 바꾼 해를 표시합니다.

A history site on how many books appeared each year, from manuscripts to e-books, and how they were counted. Each source gets its own line, and the years in which a source says it changed its counting are marked.

- 사이트 · Site: https://bowonkwon.github.io/Book-Publishing-History/

## 내용 · Contents

| 장 · Chapter | 시기 · Period |
|---|---|
| 0. 「책 한 종」을 어떻게 세나 · How do you count "one book"? | — |
| 1. 필사본에서 인쇄로 · From manuscript to print | 500–1500 |
| 2. 유럽 인쇄의 확산 · Printing spreads across Europe | 1450–1800 |
| 3. 조선의 책판과 남은 책 · Joseon woodblocks and the books that survive | 16th–19th c. |
| 4. 대량 출판의 시대 · The age of mass publishing | 1800–1945 |
| 5. 국가 통계의 시대 · The age of national statistics | 1945–1999 |
| 6. 디지털 이후 · After digital | 2000– |

## 데이터 · Data

`data/` 의 CSV(UTF-8)에는 이 사이트가 공개 서지 데이터에서 직접 센 값(VD16~18, STCN, ISTC, KORCIS)과 공식 통계표에서 옮긴 값(한국 출협, 일본 통계국, 중국 국가통계국, 미국 인구조사국, WIPO)이 있습니다. 파일마다 원자료는 사이트의 데이터 면과 방법 면에 적었습니다.

The CSV files in `data/` (UTF-8) hold values counted for this site from open bibliographic data (VD16–18, STCN, ISTC, KORCIS) and values transcribed from official tables (Korean Publishers Association, Statistics Bureau of Japan, National Bureau of Statistics of China, US Census Bureau, WIPO). The source of each file is given on the site's Data and Method pages.

## 하지 않는 것 · Scope

서로 다른 출처를 하나의 추정 줄로 잇지 않고, 인과를 말하지 않습니다. 저자·출판사 순위와 베스트셀러 목록은 다루지 않습니다.

Different sources are not spliced into one estimated line, and no causal claims are made. The site does not rank authors or publishers and does not cover bestseller lists.

## 판 이력 · Version history

판마다 자세한 내용은 사이트의 방법 면 「판 이력」에 있습니다. · Details for each version are on the site's Method page.

| 판 · Version | 날짜 · Date | 바뀐 것 · Changes |
|---|---|---|
| 1.0.5 | 2026-11-18 | 목차에서 장·절로 바로 가기(장 목록, 면 안 절 목록, 절 제목 바로가기, 처음 면의 전체 목차), 넓은 화면에서 위쪽 메뉴 고정. 본문·수치 변화 없음 · Straight from the contents to a chapter or section (chapter list, section list on each page, links on section headings, full contents on the home page); the top menu stays on wide screens. No text or numerical value changed |
| 1.0.4 | 2026-11-17 | 0장 그림의 일본 2016년 점을 출처 교체로 구분(한 출처가 밝힌 정의 변경과 따로), `definition_breaks.csv` 에 kind 칸과 미국 1959년 출처 「803쪽 본문」, 5장 일본 선의 빈 해 잇지 않기, ISTC·납본 풀이. 수치 변화 없음 · Chapter 0: Japan 2016 marked as a change of source, kept apart from definition changes stated by one source; `definition_breaks.csv` gains a kind column and the US 1959 source "p. 803 text"; the Chapter 5 Japan line no longer bridges years without values; ISTC and "deposited" explained. No numerical values changed |
| 1.0.3 | 2026-11-16 | 그래프 설명 보강(축 이름과 단위, 로그 눈금 읽는 법, 중국 선의 빈 해 잇지 않기), 휴대폰에서 그림 옆으로 넘기기, 공개 자료 허브 링크. 수치 변화 없음 · Chart explanations (axis names and units, reading log scales, China lines no longer bridge years without values), sideways scrolling on phones, hub link. No numerical values changed |
| 1.0.2 | 2026-11-15 | 그림 둘을 다시 그림(6장 ISBN 막대 눈금, 0장 연도 글자 겹침). 수치 변화 없음 · Two charts redrawn (Chapter 6 ISBN axis, Chapter 0 year labels). No numerical values changed |
| 1.0.1 | 2026-11-07 | 0장 단절 표의 1959년 UNESCO 정의 채택 출처를 「803쪽 본문」으로 바로잡음 · Chapter 0 breaks table: source for the 1959 UNESCO definition corrected to "p. 803 text" |
| 1.0.0 | 2026-11-07 | 첫 공개 · First release |

## 라이선스 · License

[LICENSE.md](LICENSE.md)

## 일러두기 · Note

이 저장소의 자료는 엮은이가 개인적으로 공부하며 엮은 것입니다. 엮은이가 속한 기관의 견해나 업무와는 관계가 없습니다.

These are personal study materials and do not represent the views or work of any institution the editor belongs to.
