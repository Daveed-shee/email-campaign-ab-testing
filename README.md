# Email Marketing A/B/C Test Analysis

## Overview
A statistical analysis of a mock email marketing campaign to determine which of 3 subject lines drives the highest open rate across 2.4 million emails.

## Key Findings
- **Subject Line 1** achieved the highest open rate at **15.89%**
- **Subject Line 3** was the weakest performer at **14.12%**
- Differences were statistically significant (χ² = 1264.51, p ≈ 0)
- Switching all emails to Subject Line 1 would generate an estimated **14,540 additional responses**

## Dataset
Mock email campaign dataset from Kaggle containing:
- `userbase.csv` — 500,000 customers with demographic info
- `sent_emails.csv` — 2.4M emails sent across 3 subject lines
- `responded.csv` — 378,000 customer responses

## Methodology
1. Calculated open rates per subject line
2. Ran a chi-square test to confirm statistical significance
3. Segmented analysis by gender and customer type to validate consistency across demographics

## Tools
- Python, pandas, matplotlib, scipy

## Results Summary
| Subject Line | Emails Sent | Open Rate |
|-------------|-------------|-----------|
| Subject Line 1 | 826,717 | 15.89% |
| Subject Line 2 | 824,837 | 15.81% |
| Subject Line 3 | 824,800 | 14.12% |

