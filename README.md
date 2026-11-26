# RupeeRise: Fact-Checking an AI-Written Investor Brief

**A FinTech case study on catching AI hallucinations before they reach investors.**

Author: [Your Name] · BBA (FinTech), Chitkara Business School · Tools: Claude, ChatGPT, Perplexity · November 2026

## The case

**RupeeRise** (fictional) is a digital lending app in Bengaluru. Its founder asked AI to write an investor brief on India's digital lending and UPI market and wanted to send it as it was. As a Business Analyst, I checked every claim against official sources before it could reach investors.

## What I did

| Step | Task | Tool |
|---|---|---|
| 1 | Generated the same brief in two AI tools | Claude, ChatGPT |
| 2 | Scored both drafts on 5 criteria | Manual |
| 3 | Listed 12 claims and asked the AI to rate its own confidence | AI + manual |
| 4 | Verified every claim against RBI, NPCI and PIB | Official websites |
| 5 | Opened every source Perplexity cited | Perplexity |

## Results

| Metric | Result |
|---|---|
| Claims checked | 12 |
| Correct | 5 |
| Outdated / Distorted / Fabricated / Unsupported | 1 / 3 / 0 / 3 |
| Rated "High confidence" by AI but wrong | 1 |
| Perplexity citations that fully supported the claim | [__ of __] |
| Tool comparison score (Claude vs ChatGPT, /10) | 8 vs [__] |

## Worst error I found

**C09:** the brief presented RBI circular RBI/2022-23/111 (2 September 2022) as the current rule for digital lenders. RBI's own page shows that circular has been repealed and replaced by the Digital Lending Directions, 2025 (RBI/2025-26/36). An investor's compliance team would spot this at once and doubt the rest of the brief.

## My top 3 "What not to do" rules

1. Never send an AI number to investors without opening the official source. (evidence: C01–C03 correct, C04–C08 not)
2. Do not treat the AI's confidence rating as proof. (evidence: C09 rated High but outdated)
3. Check who really published a figure and whether a rule is still in force. (evidence: C06, C09)

## My answer to the founder

No, the brief cannot go to investors as it is: 7 of its 12 claims were outdated, distorted or unsupported. The user and merchant counts, the market projection, the "60% of new retail loans" statistic and the cooling-off period must be verified or corrected first. The corrected version is in `07_what_not_to_do.md`.

## Skills shown

AI output evaluation · Fact-checking with official sources · Hallucination detection · Citation analysis · Responsible AI in finance · FinTech domain knowledge

## Repository files

| File | Content |
|---|---|
| `01_case_study.md` | RupeeRise case and accepted sources |
| `02_two_drafts.md` | The brief from Claude and ChatGPT |
| `03_tool_comparison.md` | Scored comparison |
| `04_claims.md` | 12 claims and AI self-rating |
| `05_hallucination_log.md` | Verification against official sources |
| `06_citation_check.md` | Perplexity citation check |
| `07_what_not_to_do.md` | Corrected brief and safe-AI guide |

## What I learned

- AI writes confident, fluent text even when facts are wrong, outdated or made up.
- Exact numbers, circular numbers, quotes and sources are where AI makes the most mistakes.
- AI's own confidence rating is not proof; only an official source is.
- A cited link is not proof either: it must be opened and must actually support the claim.
- Different AI tools give different answers to the same prompt, so tools must be compared fairly.
- For Indian finance, the official sources are RBI, NPCI, PIB and company reports.
- Nothing AI-written should reach investors or customers without a human check.

*RupeeRise and the brief in this project are fictional and created for learning.*
