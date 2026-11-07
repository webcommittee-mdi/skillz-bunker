# Exam Paper Naming Convention (ARM: all PGDM programmes)

## Format

    SUBJECT_EXAM_YEAR_Faculty Name.pdf

Example: `HBO_ET_2026_Sumita Rai.pdf`

| Part | Rule |
|---|---|
| SUBJECT | Short subject code (see table below). This is also the subject folder under PGDM-HRM. |
| EXAM | `ET` = End-Term, `MT` = Mid-Term |
| YEAR | The calendar year the exam was **held** (a single year, e.g. 2026, not 2026-28) |
| Faculty Name | The paper-setter's full name in Title Case, separated by a space, with no "Prof."/"Dr." prefix. Use the short form already used in earlier files (e.g. "Anil Pathak", not "Anil Anand Pathak"). |

Separators: use underscores between parts and a normal space inside the faculty name.

## Folder structure

Every programme uses the same flat layout:

    ARM/<Programme>/<SUBJECT folder>/<file>

e.g. `ARM/PGDM-BFS/UBFS/UBFS_MT_2026_S Veena Iyer.pdf`

- Do NOT nest by Term, exam type or faculty. The file name already carries the exam type, year and faculty.
- Do NOT repeat the programme or term in the file name (no `Term 1_PGDM-BFSI_...`).

## Official reference: `ARM/Term 1_MT/`

The official archive downloaded by the user is the source of truth for programme and subject codes, so check it before inventing a code. Its layout is `Term 1_MT/<Programme>/<SUBJECT>/files`.

| Programme folder | Official subject folders |
|---|---|
| PGDM | HBO, LAB, MA-1, MC-I, MICRO, MP, STM |
| PGDM-HRM | HBO, HRSP, MA-I, MC-I, ME, MP, STM |
| PGDM-BFS | BL, HRSP, MCM, PP, STM, UBFS |
| PGDM-BN (= Business Analytics) | BC, DMP, IS (Introduction to Statistics), LA (Linear Algebra), ME (Managerial Economics), MSM (Management Science Models), SD (Spreadsheets & Databases) |
| PGDM-IB | CL, ECO, FA, FOF, ITSB, PM (Principles of Marketing), QM, RMB, plus language papers (French/German/Spanish, which sit loose in the programme folder and are named like `German_MT_2026_Onam_Grover.pdf`) |

In file names, use the folder code without the hyphen (MA-I/MA-1 becomes MA1, MC-I becomes MC1). Courses with no official folder yet (2026 PGDM: AAM, FRA, SAID; BN: MA1) keep the codes listed below.

## Renamed / revamped subjects (leadership decision, 2026-10)

Rule: keep the existing subject folders. In the file name, write the NEW code followed by the OLD code in brackets, with the rest of the convention unchanged:
`NEW (OLD)_EXAM_YEAR[_Faculty].pdf`. A "/" can't be used because the system reads it as a folder.
- PGDM: MA-1 -> FRA: `FRA (MA1)_MT_2026.pdf` goes in `PGDM/MA-1/`
- PGDM: HBO -> SAID: `SAID (HBO)_MT_2026.pdf` goes in `PGDM/HBO/`
- PGDM: HBO -> ITLD (Interpersonal, Group & Team Dynamics for Leadership Development, ET; confirmed by the user): `ITLD (HBO)_ET_2026.pdf` goes in `PGDM/HBO/`
- PGDM Term 4: SM-2 -> CSI (Corporate Strategy and Implementation; same faculty as SM-II: Ankur Roy, Meeta Dasgupta, Shamita Garg): `CSI (SM2)_MT_2026.pdf` goes in `PGDM/SM-2/`
- PGDM: MA-1 -> FRA at end-term too: `FRA (MA1)_ET_2026.pdf` goes in `PGDM/MA-1/`
- Brand-new subjects get a NEW subject folder (leadership decision):
  - PGDM: `AAM_MT_2026.pdf` goes in a new `PGDM/AAM/`
  - PGDM: `SB_ET_2026.pdf` (Sustainability for Business; the user chose the code SB) goes in a new `PGDM/SB/`
  - PGDM-BN: `MA1_MT_2026.pdf` goes in a new `PGDM-BN/MA-1/` (folder spelled like PGDM's MA-1)
  - PGDM-BN: `PM_MT_2026_Payal Kapoor.pdf` goes in a new `PGDM-BN/PM/` (folder spelled like PGDM-IB's PM)

## Subject codes: PGDM-HRM

| Code | Subject | Folder |
|---|---|---|
| HBO | Human Behaviour in Organizations | PGDM-HRM/HBO |
| HRSP | Human Resource Systems & Processes | PGDM-HRM/HRSP |
| MA1 | Management Accounting - I | PGDM-HRM/MA-I |
| MC1 | Managerial Communication - I | PGDM-HRM/MC-I |
| ME | Microeconomics | PGDM-HRM/ME |
| MP | Marketing Planning | PGDM-HRM/MP |
| STM | Statistics for Management | PGDM-HRM/STM |

## Subject codes: PGDM-BFS

| Code | Subject | Folder |
|---|---|---|
| BL | Business Law | PGDM-BFS/BL |
| HRSP | Human Resource Systems & Processes | PGDM-BFS/HRSP |
| MCM | Marketing & Customer Management in BFS | PGDM-BFS/MCM |
| PP | Banking & Financial Services: Products & Processes | PGDM-BFS/PP |
| STM | Statistics for Management | PGDM-BFS/STM |
| UBFS | Understanding Business through Financial Statements | PGDM-BFS/UBFS |

## Subject codes: PGDM (main programme)

| Code | Subject |
|---|---|
| AAM | Applications of Analytics and AI for Managers |
| FRA | Financial Reporting & Analysis |
| MICRO | Microeconomics (official PGDM folder is MICRO; PGDM-HRM uses ME) |
| MP | Marketing Planning |
| SAID | Self-Awareness and Individual Dynamics |
| STM | Statistics for Management |

## Subject codes: PGDM-Business Analytics

| Code | Subject |
|---|---|
| BC | Business Communication |
| DMP | DMPP (printed as "DMPP" on the paper; the user's label is DMP) |
| IS | IS |
| MA1 | Management Accounting - I |
| ME | Managerial Economics (the user treats it as the same as Microeconomics, so it uses the same code) |
| PM | Principles of Marketing (official code, same as PGDM-IB) |

## Subject codes: PGDM-IB

| Code | Subject |
|---|---|
| CL | Corporate Law |
| FA | Financial Accounting |
| FOF | Fundamentals of Finance |
| ITSB | Information Tools and Skills for Business |
| QM | Quantitative Methods |
| RMB | Research Methods in Business |

## Upload batches (e.g. "Webcomm task")

An upload batch keeps the user's own programme folder names (e.g. `PGDM - HRM`, with spaces; do not rename them). Files sit **directly** in the programme folder with no subject subfolders: `<Programme>/<SUBJ>_<MT|ET>_<YEAR>[_Faculty].pdf`. Delete all hidden files (.DS_Store etc.) before upload.
Common papers covering several or all sections with multiple faculty listed (AAM, FRA, SAID, PGDM ME, HRM ME, MP) get no faculty name. If no faculty name is printed and the user doesn't know it, also leave it off.

## Special cases

1. **Global / common paper set by several faculty** (e.g. Marketing Planning): leave out the faculty part, giving `MP_ET_2026.pdf`.
2. **Faculty name not printed on the paper**: take it from the scan's original file title (e.g. `puneet arora.pdf` became `ME_ET_2026_Puneet Arora.pdf`).
3. **Older archive files that give only a year** (e.g. `HBO ET 2017-18.pdf`, `2024_ET_ME.pdf`): no faculty-specific paper was recorded for these, so they have no faculty part.
4. **Header template errors**: go by the exam date and weightage. The 2026 STM paper says "Mid-Term" in its header but was the end-term, so it was tagged `ET`.
5. **Two sections with different faculty**: the faculty name tells the two papers apart, so the section is not added to the name.
6. **Spelling of faculty names**: use the spelling printed on the paper rather than the folder or file label (e.g. Jyotsna not Jyotsana, Veena not Venna, Abu not Abhu). Keep it consistent across programmes.
7. **Filed exam type vs. header**: if the user filed a paper under Mid-Term but the header says End-Term, ask. In 2026 the user confirmed the BFSI Products & Processes paper as MT.
8. **Multiple sets by the same faculty**: if one professor set two or more different papers for the same subject and exam (e.g. separate sets for different sections), add `_1`, `_2`, `_3`… at the end of the name, e.g. `CB_ET_2026_Kirti Sharma_1.pdf`, `CB_ET_2026_Kirti Sharma_2.pdf`. Rescans of the same paper are duplicates, not sets.
9. **Name collision** (same subject, year and faculty): add `_A` or `_B` for the section.

## How to identify a paper

- Look at page 1 for "Course Name", then "Faculty Name"/"Faculty"/"Instructor"/"Facilitator", then "End-Term"/"Mid-Term".
- Adobe Scan PDFs usually have OCR text, so run `pdftotext -f 1 -l 1 file.pdf -`. If that gives nothing, OCR it with `pdftoppm -f 1 -l 1 -r 200 -png file.pdf p && tesseract p-1.png -`.
- Extra pages are often an attached case (e.g. an HBS/Ivey case), not a second paper. Check that the later pages do not start with a new MDI exam header.

## Rename log

### 2026-10-04 (Term-I end-terms, PGDM-HRM 2026-28), renamed in place in ARM

| Original scan | Renamed to | Source of faculty name |
|---|---|---|
| Adobe Scan 4 Oct 2026 (1).pdf | MP_ET_2026.pdf | Global paper (Payal S Kapoor & Vibhava Srivastava), no faculty part |
| Adobe Scan 4 Oct 2026 (2).pdf | HBO_ET_2026_Sumita Rai.pdf | Paper header (Sec B) |
| Adobe Scan 4 Oct 2026 (3).pdf | MA1_ET_2026_Ashutosh Dash.pdf | Paper header (Sec B) |
| Adobe Scan 4 Oct 2026 (4).pdf | STM_ET_2026_Saad Ashraf.pdf | Paper header (Sec A & B; header says Mid-Term, treated as ET) |
| Adobe Scan 4 Oct 2026 (6).pdf | ME_ET_2026_Vanita Singh.pdf | Paper header (Sec A) |
| Adobe Scan 4 Oct 2026 (7).pdf | MC1_ET_2026_Vidhu Gaur.pdf | Paper header (Sec A; includes BIA case) |
| Adobe Scan 4 Oct 2026.pdf | HRSP_ET_2026_Jyotsna Bhatnagar.pdf | Paper header |
| Anil Anand Pathak.pdf | HBO_ET_2026_Anil Pathak.pdf | File title (Sec A) |
| Book 4 Oct 2026.pdf | MC1_ET_2026_Neera Jain.pdf | Paper header (Sec B) |
| puneet arora.pdf | ME_ET_2026_Puneet Arora.pdf | File title (Sec B) |

### 2026-10-04 (PGDM-BFS Term-I mid-terms; folder originally PGDM-BFSI, renamed by user to PGDM-BFS), flattened from `Term 1/Mid-Term/<Subject>/<Faculty>/`

| Original (under Term 1/Mid-Term/) | Renamed to | Notes |
|---|---|---|
| BL/Parul Gupta/Term 1_PGDM-BFSI_BL_MT_2026_Parul Gupta.pdf | BL/BL_MT_2026_Parul Gupta.pdf | Faculty and MT not on the paper, taken from the folder |
| HRSP/Jyotsana Bhatnagar/Term 1_PGDM-BFSI_HRSP_MT_2026_Jyotsana Bhatnagar.pdf | HRSP/HRSP_MT_2026_Jyotsna Bhatnagar.pdf | Spelling fixed |
| MCM/Sk Abhu Khalek/Term 1_PGDM-BFSI_MCM_MT_2026_Sk Abhu Khalek.pdf | MCM/MCM_MT_2026_Sk Abu Khalek.pdf | Spelling fixed |
| Products & Processes/Neharika Sobti/Term 1_PGDM-BFSI_Products & Processes_MT_2026_Neharika Sobti.pdf | PP/PP_MT_2026_Neharika Sobti.pdf | Header says End-Term; the user confirmed MT |
| STM/Kamal Sanguri/Term 1_PGDM-BFSI_STM_MT_2026_Kamal Sanguri.pdf | STM/STM_MT_2026_Kamal Sanguri.pdf | |
| UBFS/S Venna Iyer/Term 1_PGDM-BFSI_UBFS_MT_2026_S Venna Iyer.pdf | UBFS/UBFS_MT_2026_S Veena Iyer.pdf | Spelling fixed |

The empty `Term 1/` folder tree was removed afterwards.

### 2026-10-04 (Webcomm task: Term-I mid-terms, all programmes, 34 files, renamed in place)

| Folder | Original | Renamed to |
|---|---|---|
| PGDM | AAM.pdf | AAM_MT_2026.pdf (5 faculty, common paper) |
| PGDM | FRA.pdf | FRA (MA1)_MT_2026.pdf (3 faculty, common paper; renamed subject) |
| PGDM | Marketing Planning.pdf | MP_MT_2026.pdf (global) |
| PGDM | Microeconomics.pdf | MICRO_MT_2026.pdf (4 faculty, common paper; first named ME, corrected to the official code) |
| PGDM | SAID.pdf | SAID (HBO)_MT_2026.pdf (3 faculty, common paper; renamed subject) |
| PGDM | STM.pdf | STM_MT_2026_Saad Ashraf.pdf |
| PGDM - HRM | HBO SEC A.pdf | HBO_MT_2026.pdf (no faculty printed) |
| PGDM - HRM | HBO SEC B .pdf | HBO_MT_2026_Sumita Rai.pdf |
| PGDM - HRM | HRSP SEC A&B.pdf | HRSP_MT_2026_Nidhi S Bisht.pdf |
| PGDM - HRM | MA-I SEC A.pdf | MA1_MT_2026_Shailesh Gandhi.pdf |
| PGDM - HRM | MA-I SEC B.pdf | MA1_MT_2026_Ashutosh Dash.pdf |
| PGDM - HRM | MC-I SEC A.pdf | MC1_MT_2026_Vidhu Gaur.pdf |
| PGDM - HRM | MC-I SEC B.pdf | MC1_MT_2026_Neera Jain.pdf |
| PGDM - HRM | ME SEC A&B.pdf | ME_MT_2026.pdf (Puneet Arora / Vanita Singh, common paper) |
| PGDM - HRM | MP SEC A&B.pdf | MP_MT_2026.pdf (global) |
| PGDM - HRM | STM SEC A&B.pdf | STM_MT_2026_Saad Ashraf.pdf |
| PGDM - BFS | Business Law.pdf | BL_MT_2026_Parul Gupta.pdf |
| PGDM - BFS | Human Resource Systems and Processes.pdf | HRSP_MT_2026_Jyotsna Bhatnagar.pdf |
| PGDM - BFS | Marketing and Customer Management in BFS.pdf | MCM_MT_2026_Sk Abu Khalek.pdf |
| PGDM - BFS | BFS Products and Processes.pdf | PP_MT_2026_Neharika Sobti.pdf |
| PGDM - BFS | STM.pdf | STM_MT_2026_Kamal Sanguri.pdf |
| PGDM - BFS | UBFS.pdf | UBFS_MT_2026_S Veena Iyer.pdf |
| PGDM - Business Analytics | Business Communication.pdf | BC_MT_2026_Vidhu Gaur.pdf |
| PGDM - Business Analytics | DMP.pdf | DMP_MT_2026_Prageet Aeron.pdf |
| PGDM - Business Analytics | IS.pdf | IS_MT_2026_Suwarna Shukla.pdf |
| PGDM - Business Analytics | Management Accounting I.pdf | MA1_MT_2026.pdf (no faculty printed) |
| PGDM - Business Analytics | Managerial Economics.pdf | ME_MT_2026.pdf (no faculty printed) |
| PGDM - Business Analytics | Principles of Marketing.pdf | PM_MT_2026_Payal Kapoor.pdf (first named POM, corrected to the official code) |
| PGDM - IB | Corporate Law.pdf | CL_MT_2026.pdf (no faculty printed) |
| PGDM - IB | FA SEC.pdf | FA_MT_2026.pdf (no faculty printed) |
| PGDM - IB | FOF.pdf | FOF_MT_2026_Anshul Jain.pdf |
| PGDM - IB | Information Tools and Skills for Business.pdf | ITSB_MT_2026_Anima Pramanik.pdf |
| PGDM - IB | Quantitative Methods.pdf | QM_MT_2026_Narain Gupta.pdf |
| PGDM - IB | Research Methods in Business.pdf | RMB_MT_2026_Rohit Sindhwani.pdf |
| PGDM - IB | (split from Term 1_MT/PGDM-IB/2026 PGIB Midterm Papers.pdf, pp. 13-16) | ECO_MT_2026_Rahul Kumar.pdf |
| PGDM - IB | (split from the same PDF, pp. 21-29; PM Section B) | PM_MT_2026_Neelu Bhullar.pdf |
| PGDM - IB | (split from the same PDF, pp. 30-34) | French_MT_2026_Abha Mehta.pdf |

### 2026-10-04 (PGDM ET folder: Term-I end-terms, renamed in place)

| Original | Renamed to | Notes |
|---|---|---|
| FRA.pdf | FRA (MA1)_ET_2026.pdf | Renamed subject; 3 faculty, common paper |
| ITLD.pdf | ITLD (HBO)_ET_2026.pdf | Renamed subject; 3 faculty (Rai, Pathak, Biswas) |
| LAB.pdf | LAB_ET_2026.pdf | No faculty name printed |
| Marketing Planning.pdf | MP_ET_2026.pdf | Global paper |
| Microeconomics.pdf | MICRO_ET_2026.pdf | 4 faculty, common paper |
| STM.pdf | STM_ET_2026_Saad Ashraf.pdf | Header says Mid-Term, but the date is in end-term week and it's in the ET folder, so treated as ET |
| Sustainability for Business.pdf | SB_ET_2026.pdf | New subject; 4 faculty, common paper |

### 2026-10-04 (PGDM-BN ET folder: Business Analytics Term-I end-terms, renamed in place)

| Original | Renamed to | Notes |
|---|---|---|
| Business Communication.pdf | BC_ET_2026_Neera Jain.pdf | |
| DMPP.pdf | DMP_ET_2026_Prageet Aeron.pdf | Printed as DMPP; the official folder is DMP |
| IS.pdf | IS_ET_2026_Suwarna Shukla.pdf | |
| Management Accounting I .pdf | MA1_ET_2026.pdf | New subject (new PGDM-BN/MA-1/ folder); no faculty name printed |
| Managerial Economics.pdf | ME_ET_2026.pdf | No faculty name printed |
| Principles of Marketing.pdf | PM_ET_2026_Payal Kapoor.pdf | New subject (new PGDM-BN/PM/ folder); faculty name taken from the case licence line "authorized for use only in Prof. Payal S Kapoor's Principles of Marketing" |
| S&D Question Paper ET-I.pdf | SD_ET_2026_Divya Sharma.pdf | Spreadsheets & Databases; official folder SD |

### 2026-10-11 (Term 4 PGDM end-terms, loose in ARM root, renamed in place)

The reference folders `ARM/Term 4_ET/` and `ARM/Term 4_MT/` give the Term 4 subject codes (PGDM: AGTB, AIDL, AOM, CB, CRBV, DRM, DV, ENVC, ETTA, FM, FMIB, GOB, IB, IM, LM, M&A, MBFI, MCFP, MOQ, NMS, PD, PM, RM, SCM, SDM, SM-2…).

| Original | Renamed to | Notes |
|---|---|---|
| Consumer Behaviour.pdf | CB_ET_2026_Kirti Sharma.pdf | Goes in PGDM/CB/ |
| Entrepreneurship and New Venture Creation.pdf | ENVC_ET_2026_Vinod Thakur.pdf | Same paper as the existing `Term 4_ET/PGDM/ENVC/2026_ENVC_ET_Vinod Thakur.pdf` (a different scan), so it's a duplicate |
| Pricing Decisions.pdf | PD_ET_2026.pdf | No faculty name printed; goes in PGDM/PD/ |

### 2026-10-11 (Term 4 PGDM mid-terms, loose in ARM root, renamed in place)

| Original | Renamed to | Notes |
|---|---|---|
| Consumer Behaviour MT.pdf | CB_MT_2026_Kirti Sharma.pdf | PGDM/CB/; 10 pages = paper + case |
| Corporate Strategy and Implementation.pdf | CSI (SM2)_MT_2026.pdf | Renamed subject; 3 faculty, common paper; PGDM/SM-2/ |
| Data Visualization.pdf | DV_MT_2026_Aarushi Jain.pdf | PGDM/DV/ |
| Entrepreneurship and New Venture Creation MT.pdf | ENVC_MT_2026_Vinod Thakur.pdf | PGDM/ENVC/. The existing `Envc mid term 2026.pdf` there is Vinod Thakur's PGDM-BM (38th batch) paper, a different programme, so no set number is needed |

### 2026-10-11 (Term 4 PGDM-HRM, loose in ARM root)

| Original | Result | Notes |
|---|---|---|
| PGHRM Term 4 MID term.pdf (22 pages, two papers combined) | EL2_MT_2026_Hari Parmeshwar.pdf (pp. 1-2) and SM2_MT_2026_Vinod Thakur.pdf (pp. 3-22, paper + Schindler case) | Split with qpdf; the original combined PDF is kept. Folders: PGDM-HRM/EL-2/ and SM-2/ |
| PGHR Operation Management End TERM.pdf | OM_ET_2026_Manoj K Srivastava.pdf | PGDM-HRM/OM/ |

### 2026-10-11 (Term 4 PGDM-BN, loose in ARM root)

| Original | Result | Notes |
|---|---|---|
| PGDM BN END TERM TERM 4.pdf (20 pages, combined) | AOM_ET_2026_Rohit Sindhwani.pdf (pp. 1-4) | PGDM-BN/AOM/ |
| (same) | CIB_ET_2026_Kirti Sharma.pdf (pp. 6-19, paper + Upli case) | PGDM-BN/CIB/ |
| (same) | HRM_ET_2026_Kedarnath Thakur.pdf (p. 20) | PGDM-BN/HRM/ |
| (same) p. 5 | not extracted | Ritu Srivastava's CIB ET for the 2024-26 batch (AY 2024-25), the same paper as the existing `CIB/Consumer Insights and Behavior_ET_2025_Ritu Srivastava.pdf`, so it's a duplicate |
| PGDM BN TERM 4 MID TERM CONSUMER INSIGHTS AND BEHAVIOUR.pdf | CIB_MT_2026_Ritu Srivastava.pdf | Paper + TruEarth case. Term 4_MT/PGDM - BN has no CIB folder yet, so a new one is needed |

The combined ET PDF is kept as is.

Note: the older files inside PGDM-HRM still use mixed formats (e.g. `2024_ET_HBO_AP.pdf`, `MC-I_2023_Neera Jain.pdf`) and have not been standardised yet.
