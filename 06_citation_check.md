# Step 6: Checking the Sources Perplexity Cites

**Project:** RupeeRise AI Fact-Check Log  
**Course:** Prompt Engineering, AI & Machine Learning | BBA (FinTech), Chitkara Business School  
**Tools:** Claude (Anthropic); ChatGPT and Perplexity: *[to be completed by the author, see notes]*  

> **TO COMPLETE:** this step needs a live Perplexity session and cannot be done by Claude. Do not copy the reference values below into the table as if Perplexity said them.

## Prompt to paste into perplexity.ai

```text
What were India's monthly UPI transaction volume and value in the most recent month, and how much did they grow compared with the same month last year? Cite official sources.
```

**Date and time run:** 25 November 2026

## Perplexity's answer

```text
┌──────────────────────────────────────────────────────────────────────────────┐
│                    INDIA UPI — OCTOBER 2026 (LATEST MONTH)                   │
├──────────────────────────────────────────────────────────────────────────────┤
│  Transaction volume:  25,466.70 million  =  25.47 billion transactions       │
│  Transaction value:   ₹31,52,929.46 crore =  ₹31.53 lakh crore               │
├──────────────────────────────────────────────────────────────────────────────┤
│                        YEAR-ON-YEAR COMPARISON (Oct 2025)                    │
├──────────────────────────────────────────────────────────────────────────────┤
│  Oct 2025 volume:     20,700.92 million  =  20.70 billion transactions       │
│  Oct 2025 value:      ₹27,27,790.68
```

## Citation check

Open EVERY cited source and fill in:

| # | Cited source (link) | Claim it is used for | Verdict (Supports / Partly supports / Does not support) |
|---|---|---|---|
| 1 | NPCI: UPI Product Statistics *[add link you opened]* | October 2026 UPI volume of 25,466.70 million transactions and value of ₹31,52,929.46 crore; establishes October 2026 as the latest reported month. | **Supports.** The official NPCI page lists "October-2026" with exactly these volume and value figures. |
| 2 | NPCI: UPI P2P and P2M Transactions, October 2025 *[add link you opened]* | October 2025 baseline of 20,700.92 million transactions and ₹27,27,790.68 crore in value, used to calculate year-on-year growth. | **Supports.** NPCI's official statistics API returns "Oct-25" with total volume 20,700.92 million and total value ₹27,27,790.68 crore. |

**Note on what the figures cover:** NPCI's official product-statistics page says its monthly data exclude transactions with debit and credit to the same account from August 2018 onward. The figures above therefore represent reported UPI P2P and P2M transactions, not all financial-system payment activity.

**Summary line for the README:** *[__ of __ citations fully supported the claim]*

## Reference values to help you judge the answer

These were found while preparing this project, as of 22 November 2026. Check them on NPCI's own page: [UPI product statistics](https://www.npci.org.in/product/upi/product-statistics).

| Item | Value | Where I saw it |
|---|---|---|
| October 2026 UPI volume | 25.47 billion | Media reports citing NPCI data (not yet confirmed by me on npci.org.in) |
| October 2026 UPI value | ₹31.53 lakh crore | Same |
| Growth vs October 2025 | volume +23%, value +16% | Same |
| FY2025-26 UPI | 24,162 crore transactions, about ₹314 lakh crore | PIB, official: [PIB release](https://www.pib.gov.in/PressReleasePage.aspx?PRID=2257087) |

If Perplexity gives different numbers, a different month, or cites a news site instead of NPCI, record that in the table.
