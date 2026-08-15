# Courseware QA Report — v11.0

**Course:** Advanced Transactional Accounting with QuickBooks Online  
**Course code:** TGS-2023018989  
**Audit date:** 16 August 2026  
**Overall verdict:** PASS

The audit followed the current published Tertiary Infotech WSQ courseware checklist, the installed `/courseware-qa` command, and the source-alignment requirements for this course. The 312-slide legacy deck was treated as the coverage floor; the rebuilt courseware relocates click-by-click procedures to the Learner Guide and activities while expanding advanced control, reconciliation, close, reporting, and Singapore reporting-framework depth.

## A. PPT Quality Audit — PASS

- 139-slide, 16:9, concept-led visual deck rendered in full and reviewed through five complete contact sheets.
- Separate general trainer template and Dr Alfred Ang profile on slides 3–4.
- Visual Download Course Material flow on slide 15 with a live LMS link.
- Practice Exam visual on slide 16 with a live Tertiary Exams link.
- Assessment Flow visuals at the front and end; final sequence is slides 136–139: Assessment, Assessment Flow, Digital Attendance, Thank You.
- Version 11.0 appears once on the cover and matches the live PPTX/PDF filename.
- Four editable native PowerPoint charts; 139 fade transitions; no rasterised legacy slides.
- No click-by-click QuickBooks procedure slides, visible truncation ellipses, clipped objects, or placeholder content.

## B. Assessment Quality Audit — PASS

- Live approved structure preserved: WA with 3 open-ended questions and PP with 3 practical tasks, 1 hour per instrument.
- Four DOCX files: WA paper/key and PP paper/key. Each carries the correct course, instrument, criterion codes, and WSQ cover.
- Candidate papers: page 1 cover; page 2 Trainee Information, Instructions, LMS link, and Grading / For Official Use Only; questions or scenario start on page 3.
- PP remains Practical Performance and aligns to the learner activities. No multiple-choice items.
- Answer keys are trainer-only and excluded from GitHub and LMS attachment scope.

| Criterion | Assessment item | Course evidence |
|---|---|---|
| K1 | WA Question 1 | Topic 1 slides 18–70; Activities 3, 4, 8 |
| K2 | WA Question 2 | Topic 2 slides 72–103; Activities 7, 10, 11 |
| K3 | WA Question 3 | Topic 3 slides 105–132; Activities 8, 12 |
| A1 | PP Task 1 | Activities 2, 3, 4, 7, 8, 12 |
| A2 | PP Task 2 | Activities 10, 12 |
| A3 | PP Task 2 | Activities 10, 12 |
| A4 | PP Task 3 | Activity 12 |

## C. Lesson Plan — PASS

- WSQ cover, Document Version Control Record, Word TOC field, Arial body, and Page X of Y footer present.
- Day 1 and Day 2 each contain 480 scheduled non-lunch minutes.
- Current slide ranges and all 12 activity mappings validate within the 139-slide deck.
- WA and PP durations, instrument types, criteria, and Day 2 assessment block align to the papers.

## D. Learner Guide — PASS

- WSQ cover, Document Version Control Record, Word TOC field, Arial body, and Page X of Y footer present.
- 38 rendered pages visually reviewed; detailed QuickBooks procedures appear here and in the activity guides, not in the PPT.
- Twelve-activity roadmap and self-contained detailed activity sections are present.
- Markdown mirror uses the same single-source content and references only files that actually exist.

## E. Activities and Alignment — PASS

- 12 individual `activities/activity-*` folders; no learner-facing `labs/` folder or lab references.
- Every folder contains one detailed Markdown guide, one workflow visual, one formula-driven Excel control workbook, and 3–7 realistic CSV source files.
- Every workbook contains Read Me, Source Register, Exceptions, Acceptance Tests, Evidence Log, and Control Calculations sheets; at least 12 formulas and zero formula errors after recalculation.
- Corrected workflow visuals use contained two-line labels. Assessment, deck, Learner Guide, and Lesson Plan trace to the same activities.

## F. Files, Versions, and Distribution — PASS

- One live v11.0 trainer deck and matching PDF; current Learner Guide and Lesson Plan DOCX/PDF files present.
- All PPTX, DOCX, and XLSX packages pass ZIP integrity checks; all PDFs pass `pdfinfo` validation.
- `.env`, `assessment/`, `reference/`, build sources, assets, and QA renders are excluded from the public GitHub release.
- Drive/LMS publication must use question papers only for learner-facing assessment links; answer keys remain trainer-only.

