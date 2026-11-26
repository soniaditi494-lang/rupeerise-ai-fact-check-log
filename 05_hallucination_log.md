# Step 5: Verification Against Official Sources

**Project:** RupeeRise AI Fact-Check Log  
**Course:** Prompt Engineering, AI & Machine Learning | BBA (FinTech), Chitkara Business School  
**Tools:** Claude (Anthropic); ChatGPT and Perplexity: *[to be completed by the author, see notes]*  

Each claim from `04_claims.md` was checked against RBI, PIB or NPCI. Non-official pages (such as Inc42) were used only to trace where a figure came from, never as proof.

> **Author's action:** open every link below yourself and confirm the verdict before submitting. NPCI's own statistics page could not be opened during preparation, so UPI figures were checked on RBI's Payment System Indicators page (which publishes the same NPCI data) and PIB. Open [NPCI product statistics](https://www.npci.org.in/product/upi/product-statistics) and add a line confirming C01 to C05.

## Verification log

| ID | AI claim | What the official source says (with link) | Verdict |
|---|---|---|---|
| C01 | UPI processed 20.0 billion transactions … in August 2025 (Source: NPCI) | RBI Payment System Indicators, August 2025: UPI volume 2,00,083.10 lakh (= 20.01 billion) for August 2025. [https://rbi.org.in/SCRIPTs/PSIUserView.aspx?Id=51](https://rbi.org.in/SCRIPTs/PSIUserView.aspx?Id=51) The data is NPCI's; also open NPCI's own page: [https://www.npci.org.in/product/upi/product-statistics](https://www.npci.org.in/product/upi/product-statistics) | **Correct** |
| C02 | … worth ₹24.9 lakh crore in August 2025 | Same RBI page: UPI value ₹24,85,473 crore (= ₹24.85 lakh crore) for August 2025. The draft's ₹24.9 lakh crore is this figure rounded. [https://rbi.org.in/SCRIPTs/PSIUserView.aspx?Id=51](https://rbi.org.in/SCRIPTs/PSIUserView.aspx?Id=51) | **Correct** |
| C03 | roughly 34% more than a year earlier | Same RBI page: August 2024 UPI volume 1,49,630.47 lakh vs August 2025 2,00,083.10 lakh = +33.7%, which rounds to about 34%. [https://rbi.org.in/SCRIPTs/PSIUserView.aspx?Id=51](https://rbi.org.in/SCRIPTs/PSIUserView.aspx?Id=51) | **Correct** |
| C04 | UPI now has over 350 million active users | No active-user figure appears on the PIB release ([https://www.pib.gov.in/PressReleasePage.aspx?PRID=2257087](https://www.pib.gov.in/PressReleasePage.aspx?PRID=2257087)) or the RBI Payment System Indicators page ([https://rbi.org.in/SCRIPTs/PSIUserView.aspx?Id=51](https://rbi.org.in/SCRIPTs/PSIUserView.aspx?Id=51)), which give transactions, value and banks live. *Author to also search NPCI's website before finalising.* | **Unsupported** |
| C05 | … and more than 50 million merchants (Source: NPCI) | No merchant count found on the same official pages. The RBI page lists UPI QR codes (about 6,978 lakh in August 2025), which is a different measure from merchants. [https://rbi.org.in/SCRIPTs/PSIUserView.aspx?Id=51](https://rbi.org.in/SCRIPTs/PSIUserView.aspx?Id=51) *Author to also check NPCI.* | **Unsupported** |
| C06 | India's digital lending market is projected to reach $1.3 trillion by 2030 (Source: BCG–Google report) | The $1.3 trillion by 2030 figure comes from an Inc42 report (State of Indian Fintech Ecosystem, Q3 2022), not a BCG–Google report: [https://inc42.com/buzz/digital-lending-become-1-3-tn-market-2030-india/](https://inc42.com/buzz/digital-lending-become-1-3-tn-market-2030-india/). It is a 2022 media-report projection, not an official source. | **Distorted** |
| C07 | … growing at about 22% a year (Source: BCG–Google report) | The 22% is Inc42's projected CAGR for 2022 to 2030 (from $270 billion in 2022), not a BCG–Google figure: [https://inc42.com/buzz/digital-lending-become-1-3-tn-market-2030-india/](https://inc42.com/buzz/digital-lending-become-1-3-tn-market-2030-india/). | **Distorted** |
| C08 | Digital lending already accounts for around 60% of all new retail loans by value (Source: RBI Financial Stability Report) | Searches of RBI Financial Stability Report coverage and RBI's digital lending publications found no statement that digital lending is about 60% of new retail loans by value. A figure of 60% does appear in Inc42's report, but about digital lending's projected share of the *fintech market* by 2030, a different claim. *Author to confirm in the FSR PDFs on rbi.org.in.* | **Unsupported** |
| C09 | RBI Guidelines on Digital Lending (circular RBI/2022-23/111, dated 2 September 2022) require loans to be disbursed directly into the borrower's bank account | The circular number and date are real (RBI/2022-23/111, 2 Sept 2022), but RBI's page says the circular has been repealed ([https://www.rbi.org.in/scripts/FS_Notification.aspx?Id=12382](https://www.rbi.org.in/scripts/FS_Notification.aspx?Id=12382)). It is repealed by the 2025 Directions (para 30 and Annex III: [https://www.rbi.org.in/Scripts/BS_ViewMasDirections.aspx?id=12848](https://www.rbi.org.in/Scripts/BS_ViewMasDirections.aspx?id=12848)). The direct-disbursal rule itself continues in para 9 of the 2025 Directions. | **Outdated** |
| C10 | RBI (Digital Lending) Directions, 2025 (issued 8 May 2025) | RBI Master Directions page: Reserve Bank of India (Digital Lending) Directions, 2025, RBI/2025-26/36, dated May 8, 2025. [https://www.rbi.org.in/Scripts/BS_ViewMasDirections.aspx?id=12848](https://www.rbi.org.in/Scripts/BS_ViewMasDirections.aspx?id=12848) | **Correct** |
| C11 | … require a Key Fact Statement before loan execution | Para 8(i) of the Directions requires REs to provide a Key Fact Statement under RBI's KFS circular of 15 April 2024. [https://www.rbi.org.in/Scripts/BS_ViewMasDirections.aspx?id=12848](https://www.rbi.org.in/Scripts/BS_ViewMasDirections.aspx?id=12848) *The exact "before execution" timing is in that KFS circular, which the author should open too.* | **Correct** |
| C12 | … a cooling-off period of at least three days during which borrowers can exit a loan without penalty | Para 10 of the Directions: the cooling-off period is determined by the RE's Board, subject to *not being less than one day*, not three days. The borrower exits by paying principal and proportionate APR; a one-time processing fee may be retained. [https://www.rbi.org.in/Scripts/BS_ViewMasDirections.aspx?id=12848](https://www.rbi.org.in/Scripts/BS_ViewMasDirections.aspx?id=12848) | **Distorted** |

## Counts

| Verdict | Number of claims |
|---|---|
| Correct | 5 |
| Outdated | 1 |
| Distorted | 3 |
| Fabricated | 0 |
| Unsupported | 3 |
| **Total checked** | **12** |
| **Not Correct** | **7** (the lab requires at least 5, so the optional trap questions were not needed) |

## Rated "High confidence" by the AI but not Correct

**1 claim:** C09 (rated High, but the circular has been repealed). Claims rated Medium or Low that were not Correct: C04, C05, C06, C07, C08, C12. The AI's confidence level was therefore a poor guide to whether a claim was right: the claims it rated "High" were mostly correct, but it also rated the repealed circular High and rated four precise figures only Medium.

## What I noticed

- The **UPI numbers (C01 to C03) were all correct**, which makes the draft look reliable. The errors sit in the surrounding claims: user counts, market projections, a statistic attributed to RBI, and rule details.
- Two errors (C06, C07) are **misattributions**: real numbers credited to the wrong publisher.
- C12 is a **small number change** (three days instead of one) that a lender's compliance team would spot immediately.
