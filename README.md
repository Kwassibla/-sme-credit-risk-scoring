# Data-Driven Credit Risk & Liquidity Scoring for SMEs

**INCO Academy Advanced Data Analytics Capstone | Presented to Okta Mentors**

## Business Context
Across African financial markets, liquidity exists yet rarely reaches small and medium-sized enterprises (SMEs) due to rigid, collateral-heavy banking underwriting. This project demonstrates how **SQL and Python (Pandas, Seaborn)** can evaluate creditworthiness using cash-flow ratios rather than legacy credit history alone.

## Methodology & Key Insights
- **Data Governance & Imputation:** Audited 614 loan applications, preserving 100% of thin-file applicants via median loan imputation and prudent zero-flagging for undocumented credit histories.
- **Financial Feature Engineering:** Constructed a standardised `Loan_to_Income` multiple (Loan Amount / Annualised Total Income) and segmented applicants into a **3-Tier Credit Risk Matrix** (*Low*, *Moderate*, and *High Risk*).
- **Core Finding:** *Moderate-Risk* borrowers (verified history, higher leverage > 2.0x) exhibit the **lowest historical risk rate (18.6%)** while requesting larger tickets (`156k` avg), whereas *High-Risk* thin-file applicants face a **68.3% rejection rate** despite normal debt burdens (`2.05x`).

## Repository Contents
- `Capstone_Credit_Risk_SME.ipynb`: Full Python notebook covering data cleaning, ratio engineering, 3-tier risk scoring, and executive visualisations.
