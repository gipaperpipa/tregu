# Accuracy audit

**2026-11-14.** 50 figures drawn at random (seed 20261114) from the 7,701 figures Tregu publishes that were read by machine, and each one compared by eye with the PDF page it links to.

**48 of 50 matched the page exactly (96%; 95% interval 87–99%).** Both mismatches came from how the build assembled figures, not from misread digits. Both causes are fixed, and the fixes corrected the same defect elsewhere in the data. 1 figure of 50 was shown under the wrong company; that link is corrected.

Statements read by hand (ChatGPT) were left out: they were checked page by page when they were imported, and would flatter the result.

| # | Company | Year | Figure | Published (€) | Page | Result |
|---|---|---|---|---|---|---|
| 1 | KIVO L.L.C | 2021 | Total assets | 12,489,474 | [p. 6](https://mf.rks-gov.net/desk/content/media/58fdc789-30b3-4ccc-9459-b38a0db32bf0.pdf#page=6) | ✔ |
| 2 | Dukagjini SH.P.K | 2023 | Equity | 64,283,048 | [p. 8](https://mf.rks-gov.net/desk/content/media/3fb51e4f-7e3b-4fae-aeb8-470a22103006.pdf#page=8) | ✘ Equity derived from consolidated total assets minus liabilities taken from a different filing (the separate statements). The page shows equity of 56,774,791. Fixed: a derived total now requires both inputs from the same filing; this figure is withheld. |
| 3 | SPORTINA ALBI L.L.C PRISHTINE | 2014 | Net profit | 90,349 | [p. 3](https://mf.rks-gov.net/desk/content/media/0853c371-e63d-47ab-93c2-f280e8e100ca.pdf#page=3) | ✔ |
| 4 | VAM - TRADE SH.P.K | 2025 | Revenue | 9,033,654 | [p. 7](https://mf.rks-gov.net/desk/content/media/c742d9e4-9a61-4980-a9c8-608ac4c6e2e5.pdf#page=7) | ✔ |
| 5 | ALBI FASHION SH.P.K | 2023 | Total assets | 6,154,563 | [p. 6](https://mf.rks-gov.net/desk/content/media/42db18a0-64ae-4faa-aad0-3b07d125964b.pdf#page=6) | ✔ |
| 6 | H & M Hennes & Mauritz Kosovo SH.P.K | 2025 | Equity | -82,540 | [p. 6](https://mf.rks-gov.net/desk/content/media/0a00eb44-1ed0-4a11-864f-eace2e3fef4d.pdf#page=6) | ✔ Derived −82,540; the page prints (82,541), a €1 rounding in the statement. |
| 7 | GE Vernova International Branch in Kosovo | 2018 | Revenue | 17,275 | [p. 6](https://mf.rks-gov.net/desk/content/media/c0f1bfa8-9b11-4714-a8c9-fdc4f0a8d6e6.pdf#page=6) | ✘ A 'Deferred revenues' liability was labelled revenue alongside the real revenue line; the build took the first. The page shows revenue of 5,024,036. Fixed: each figure is now read from its own statement, as its proof was; 38 figures across the corpus were affected. |
| 8 | A.S. ALBERTI SH.P.K | 2024 | Revenue | 35,500,387 | [p. 6](https://mf.rks-gov.net/desk/content/media/fc0cb840-5b50-4495-811e-9be80e6e8e33.pdf#page=6) | ✔ |
| 9 | R & Rukolli SH.P.K | 2021 | Equity | 16,506,779 | [p. 6](https://mf.rks-gov.net/desk/content/media/384d6c03-1ca3-4fab-9431-13672250677d.pdf#page=6) | ✔ |
| 10 | Birra Peja SH.A | 2024 | Total assets | 137,362,000 | [p. 8](https://mf.rks-gov.net/desk/content/media/02c9cf5f-0d07-4b35-ae47-b300ac3c28fc.pdf#page=8) | ✔ Printed in thousands of euro; scaled correctly. |
| 11 | Rinas Trade | 2017 | Net profit | 281,906 | [p. 7](https://mf.rks-gov.net/desk/content/media/ced949b3-4ef7-4838-a39f-f506d66daca2.pdf#page=7) | ✔ |
| 12 | AL - TRADE CENTER SH.P.K | 2019 | Revenue | 8,731,640 | [p. 9](https://mf.rks-gov.net/desk/content/media/4271fbe7-febd-43d7-911c-0b945f9b93ef.pdf#page=9) | ✔ |
| 13 | ALBI FASHION SH.P.K | 2025 | Equity | 4,852,210 | [p. 6](https://mf.rks-gov.net/desk/content/media/6fd72819-325e-4f2d-a826-815494a17856.pdf#page=6) | ✔ |
| 14 | ALBA GROUP SH.P.K | 2021 | Net profit | 677,191 | [p. 10](https://mf.rks-gov.net/desk/content/media/aac8e66a-541a-48c4-bcd1-2f879acb0e1f.pdf#page=10) | ✔ |
| 15 | MYWINGS AVIATION SH.P.K | 2025 | Total assets | 5,592,046 | [p. 7](https://mf.rks-gov.net/desk/content/media/14ca8815-462d-490e-9c49-9dce92568098.pdf#page=7) | ✔ |
| 16 | Plus Market group | 2023 | Revenue | 10,186,145 | [p. 8](https://mf.rks-gov.net/desk/content/media/9c379861-05f6-44ab-8f22-c62d6e86d31b.pdf#page=8) | ✔ |
| 17 | N.T. Rimida | 2018 | Equity | 3,614,783 | [p. 3](https://mf.rks-gov.net/desk/content/media/7547bd6f-e2ea-400d-967a-fdf34240c9b7.pdf#page=3) | ✔ |
| 18 | FRUTTI | 2021 | Equity | 1,851,126 | [p. 6](https://mf.rks-gov.net/desk/content/media/44c35ec3-7cfe-4379-a58f-195dd972bc33.pdf#page=6) | ✔ |
| 19 | ALMA MATER EUROPAEA CAMPUS COLLEGE REZONANCA & POLIKLINIKA REZONANCA SH.P.K | 2021 | Revenue | 6,203,729 | [p. 7](https://mf.rks-gov.net/desk/content/media/fe5f4455-fa14-44ab-9c1c-a5a1f805d18f.pdf#page=7) | ✔ The statement misprints both column headers as 2021; the prior-year column was read. |
| 20 | BUÇAJ SH.P.K | 2017 | Total assets | 61,440,000 | [p. 5](https://mf.rks-gov.net/desk/content/media/e7096f9d-6322-444c-8402-c24555e75a7f.pdf#page=5) | ✔ Printed in thousands of euro; scaled correctly. |
| 21 | Komtel Project Engineering SH.P.K | 2019 | Revenue | 1,700,231 | [p. 6](https://mf.rks-gov.net/desk/content/media/6bb1ea87-af37-4dff-9cfb-a4a18e0123c2.pdf#page=6) | ✔ |
| 22 | Fluidi SH.P.K | 2016 | Revenue | 16,010,235 | [p. 8](https://mf.rks-gov.net/desk/content/media/06fd1a47-3a68-4770-a517-b171a138ac98.pdf#page=8) | ✔ |
| 23 | MINERAL L.L.C | 2019 | Revenue | 13,135,858 | [p. 8](https://mf.rks-gov.net/desk/content/media/c2ccf8c5-b728-4d25-8ff7-30303b916f18.pdf#page=8) | ✔ |
| 24 | Inter Çadra SH.P.K | 2024 | Equity | 2,373,993 | [p. 6](https://mf.rks-gov.net/desk/content/media/7f23aa08-01bd-4562-8105-56d4027ff5ba.pdf#page=6) | ✔ Value right, company wrong: INTER ADRIA L.L.C.'s statements were credited by fuzzy matching to Inter Çadra SH.P.K. Fixed: linked to InterAdria L.L.C. (810819336). |
| 25 | MS H & BT | 2025 | Net profit | 4,524,186 | [p. 8](https://mf.rks-gov.net/desk/content/media/8978643d-1686-421b-b77e-1cd3c5703c81.pdf#page=8) | ✔ Right company, shown by its trade name 'MS H & BT'. Fixed: initials now give way to the legal name. |
| 26 | Agro Kor SH.P.K | 2023 | Net profit | 197,124 | [p. 8](https://mf.rks-gov.net/desk/content/media/12918e7e-cc8a-4e6b-90da-fe4322419d31.pdf#page=8) | ✔ |
| 27 | ENTERNET SH.P.K | 2018 | Net profit | 1,380,713 | [p. 7](https://mf.rks-gov.net/desk/content/media/41629dde-c9d6-4f3a-8dfd-71e0079363b7.pdf#page=7) | ✔ |
| 28 | Lika Trade SH.P.K | 2021 | Total assets | 8,745,433 | [p. 6](https://mf.rks-gov.net/desk/content/media/e311dd68-bea7-433e-991c-7b42f957df7e.pdf#page=6) | ✔ |
| 29 | LIRIDONI DISTRIBUTION | 2021 | Equity | 5,858,518 | [p. 7](https://mf.rks-gov.net/desk/content/media/439c91c6-7c39-44c9-a2bd-2d471581be75.pdf#page=7) | ✔ |
| 30 | Auloni SH.P.K | 2019 | Revenue | 13,434,463 | [p. 7](https://mf.rks-gov.net/desk/content/media/0fdbadf1-0db5-4dda-bc17-c362eb7156ed.pdf#page=7) | ✔ |
| 31 | Meridian Corporation SH.P.K | 2020 | Total assets | 20,595,520 | [p. 6](https://mf.rks-gov.net/desk/content/media/627caf4b-730a-405a-b170-f1e2ba2f111a.pdf#page=6) | ✔ |
| 32 | Hib Petrol SH.P.K | 2023 | Revenue | 167,842,000 | [p. 31](https://mf.rks-gov.net/desk/content/media/14b91299-a5c8-4d67-bb96-3af2cb020543.pdf#page=31) | ✔ Printed in thousands. The statements are HIB Holding's consolidated accounts, filed under Hib Petrol's name and shown under it. |
| 33 | AUTOTRADE SH.P.K | 2024 | Total assets | 9,292,179 | [p. 6](https://mf.rks-gov.net/desk/content/media/7efb02b6-8170-4e9a-b399-b67ed1a2217c.pdf#page=6) | ✔ |
| 34 | Ujë Rugove SH.P.K | 2025 | Equity | 7,333,197 | [p. 6](https://mf.rks-gov.net/desk/content/media/ada67821-2ec4-4112-9841-4dd173241ae1.pdf#page=6) | ✔ |
| 35 | Ndërtimtari SH.P.K | 2016 | Revenue | 4,699,692 | [p. 7](https://mf.rks-gov.net/desk/content/media/6878c8f3-fd90-4591-94dc-99ed3c1671b0.pdf#page=7) | ✔ |
| 36 | Royal Beverage | 2022 | Total assets | 6,274,961 | [p. 8](https://mf.rks-gov.net/desk/content/media/82d0e119-0336-4118-9bd6-cc8fcf5f2d1d.pdf#page=8) | ✔ |
| 37 | SHALA SWISS OIL SH.P.K | 2023 | Revenue | 7,603,048 | [p. 7](https://mf.rks-gov.net/desk/content/media/2d81f508-79da-4b39-80a9-9de77cd27ee7.pdf#page=7) | ✔ |
| 38 | American School of Kosova SHPK | 2018 | Net profit | 46,133 | [p. 7](https://mf.rks-gov.net/desk/content/media/867949ad-66a2-45d9-816f-131c6ed2552b.pdf#page=7) | ✔ |
| 39 | Pofix SH.P.K | 2024 | Total assets | 20,393,226 | [p. 6](https://mf.rks-gov.net/desk/content/media/e9c3aa63-88b8-4248-972f-9cd21ea51954.pdf#page=6) | ✔ |
| 40 | Fluidi SH.P.K | 2014 | Net profit | 1,049,598 | [p. 4](https://mf.rks-gov.net/desk/content/media/d4c7e302-d085-4d39-be85-183cee62b9dc.pdf#page=4) | ✔ |
| 41 | MODEL SLOVENIA SH.P.K | 2017 | Revenue | 11,614,202 | [p. 6](https://mf.rks-gov.net/desk/content/media/6a1d191f-0954-4481-be8f-ce7d77b282d8.pdf#page=6) | ✔ |
| 42 | Rec Kos SH.P.K | 2022 | Net profit | 3,391,007 | [p. 7](https://mf.rks-gov.net/desk/content/media/77e11849-92bd-4a66-95f4-fc75c4571aa3.pdf#page=7) | ✔ |
| 43 | VAM - TRADE SH.P.K | 2022 | Revenue | 20,138,969 | [p. 7](https://mf.rks-gov.net/desk/content/media/442eb582-cf5c-4dff-a75b-609438ae80dd.pdf#page=7) | ✔ |
| 44 | EUROFOOD SH.P.K | 2019 | Total assets | 12,560,895 | [p. 7](https://mf.rks-gov.net/desk/content/media/423469ee-3653-4a8c-89b6-d7d8845384fb.pdf#page=7) | ✔ |
| 45 | Trema Engineering shpk | 2018 | Equity | 311,600 | [p. 5](https://mf.rks-gov.net/desk/content/media/6434759b-3525-4ff2-897d-8ebe78197d7e.pdf#page=5) | ✔ Filer not matched to the registry; shown under its own name. |
| 46 | Reforma SH.P.K | 2019 | Total assets | 11,525,116 | [p. 7](https://mf.rks-gov.net/desk/content/media/efef47ae-8289-4419-b829-a4a7d918ef6c.pdf#page=7) | ✔ |
| 47 | METALTEKNIKA ASLLANI | 2023 | Revenue | 12,565,780 | [p. 9](https://mf.rks-gov.net/desk/content/media/85432370-c30c-4d64-89bf-89954ae13e41.pdf#page=9) | ✔ |
| 48 | Company21 P. e konsoliduara | 2018 | Equity | 2,428,000 | [p. 6](https://mf.rks-gov.net/desk/content/media/d0ba4065-ece5-4671-9be7-1d6504acb06a.pdf#page=6) | ✔ Printed in thousands of euro; scaled correctly. |
| 49 | ERICSSON NiKOLA TESLA D.d. - BRANCH OFFICE OF KOSOVO Dega në Kosovë | 2024 | Revenue | 17,032,649 | [p. 7](https://mf.rks-gov.net/desk/content/media/ba4ccd7d-9ff9-47d7-b7d1-77c900eedecf.pdf#page=7) | ✔ |
| 50 | QAK | 2017 | Net profit | 4,021,000 | [p. 6](https://mf.rks-gov.net/desk/content/media/3915799d-5bff-4c1b-9f9f-f76aec4b79ff.pdf#page=6) | ✔ Right company, shown by its trade name 'QAK'. Fixed: shown as EUROLAB SH.P.K (QAK). |

Values printed in thousands are compared after scaling. "Published" is the value the site showed when the sample was drawn.
