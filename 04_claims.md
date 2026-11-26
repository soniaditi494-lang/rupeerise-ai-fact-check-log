# Step 4: Every Claim Listed, and the AI's Self-Rating

**Project:** RupeeRise AI Fact-Check Log  
**Course:** Prompt Engineering, AI & Machine Learning | BBA (FinTech), Chitkara Business School  
**Tools:** Claude (Anthropic); ChatGPT and Perplexity: *[to be completed by the author, see notes]*  

**Draft chosen:** Draft 1 (Claude), see `02_two_drafts.md`.

## Part A: Checkable claims (copied from the draft)

| ID | Claim (copied exactly) | Type |
|---|---|---|
| C01 | UPI processed 20.0 billion transactions … in August 2025 (Source: NPCI) | Number |
| C02 | … worth ₹24.9 lakh crore in August 2025 | Number |
| C03 | roughly 34% more than a year earlier | Number |
| C04 | UPI now has over 350 million active users | Number |
| C05 | … and more than 50 million merchants (Source: NPCI) | Number |
| C06 | India's digital lending market is projected to reach $1.3 trillion by 2030 (Source: BCG–Google report) | Number / Source |
| C07 | … growing at about 22% a year (Source: BCG–Google report) | Number / Source |
| C08 | Digital lending already accounts for around 60% of all new retail loans by value (Source: RBI Financial Stability Report) | Number / Source |
| C09 | RBI Guidelines on Digital Lending (circular RBI/2022-23/111, dated 2 September 2022) require loans to be disbursed directly into the borrower's bank account | RBI rule |
| C10 | RBI (Digital Lending) Directions, 2025 (issued 8 May 2025) | RBI rule |
| C11 | … require a Key Fact Statement before loan execution | RBI rule |
| C12 | … a cooling-off period of at least three days during which borrowers can exit a loan without penalty | RBI rule |

12 claims. No quotation is listed because the draft did not contain one.

## Part B: The AI rates its own work

Prompt used:

```text
Here is the investor brief you wrote. List every factual claim in it.

For each claim, tell me:
1. How confident you are that it is correct (High / Medium / Low)
2. Whether it could be out of date
3. Exactly where I can verify it

Output a table: ID | Claim | Confidence | Could be outdated? | Where to verify

Brief:

[the Claude draft from 02_two_drafts.md]
```

### AI output

| ID | Claim | Confidence | Could be outdated? | Where to verify |
|---|---|---|---|---|
| C01 | UPI processed 20.0 billion transactions … in August 2025 (Source: NPCI) | High | No for August 2025 itself; newer months exist | NPCI UPI product statistics |
| C02 | … worth ₹24.9 lakh crore in August 2025 | High | No for August 2025 itself; newer months exist | NPCI UPI product statistics |
| C03 | roughly 34% more than a year earlier | High | No (calculated from August 2024 data) | NPCI UPI product statistics |
| C04 | UPI now has over 350 million active users | Medium | Yes, user counts change quickly | NPCI or a company report; the exact figure may not be published |
| C05 | … and more than 50 million merchants (Source: NPCI) | Medium | Yes | NPCI ecosystem data |
| C06 | India's digital lending market is projected to reach $1.3 trillion by 2030 (Source: BCG–Google report) | Medium | Yes, projections date quickly | The original report named as the source |
| C07 | … growing at about 22% a year (Source: BCG–Google report) | Medium | Yes | The original report named as the source |
| C08 | Digital lending already accounts for around 60% of all new retail loans by value (Source: RBI Financial Stability Report) | Low | Yes | RBI Financial Stability Report (check the exact edition and page) |
| C09 | RBI Guidelines on Digital Lending (circular RBI/2022-23/111, dated 2 September 2022) require loans to be disbursed directly into the borrower's bank account | High | Possibly, rules get replaced | RBI Notifications / Index to RBI Circulars |
| C10 | RBI (Digital Lending) Directions, 2025 (issued 8 May 2025) | High | Possibly, rules get amended | RBI Master Directions |
| C11 | … require a Key Fact Statement before loan execution | High | Possibly, rules get amended | RBI Master Directions |
| C12 | … a cooling-off period of at least three days during which borrowers can exit a loan without penalty | Medium | Yes, rules get amended | RBI Master Directions (cooling-off paragraph) |

> **Note on how this table was produced:** the self-rating was prepared by Claude in the same working session in which the draft was fact-checked. A clean test would run this prompt in the *same chat that wrote the draft, before any checking*. To make this step fully your own evidence, repeat Part B in your own chat and replace this table with the real output, then recount the "High but wrong" figure in Step 5.

## What to notice

The AI rated only one of the claims "Low" (C08, the 60% figure). It rated the old 2022 circular (C09) "High" even though it can be replaced. See Step 5 for whether its confidence was deserved.
