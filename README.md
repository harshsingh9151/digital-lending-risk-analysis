# Digital Lending Risk Analytics & Credit Strategy Simulation

## Overview

This project simulates a realistic digital lending ecosystem and analyzes portfolio performance, credit risk behavior, acquisition efficiency, and profitability across multiple lending products.

The objective was to evaluate how a fintech lender can balance aggressive growth with sustainable portfolio quality using data-driven credit policy strategies.

The project was developed as part of a summer analytics initiative focused on credit risk strategy and portfolio analytics.

---

# Business Problem

Digital lending institutions often face the challenge of:

* scaling customer acquisition rapidly,
* managing rising delinquency rates,
* optimizing pricing and underwriting policies,
* and improving risk-adjusted profitability.

This project explores how customer behavior, acquisition channels, loan structures, and behavioral signals influence portfolio outcomes and how lenders can proactively manage risk without compromising growth.

---

# Project Objectives

The analysis focuses on answering the following strategic questions:

* Which customer segments exhibit materially different repayment behavior?
* Which acquisition channels drive the best long-term portfolio quality?
* Which products and tenures generate the strongest risk-adjusted returns?
* How can pricing and approval strategies be optimized across borrower segments?
* Which behavioral indicators can help identify delinquency risk early?

---

# Dataset Design

A fully synthetic lending portfolio dataset was designed and enriched to simulate a realistic unsecured lending environment.

The ecosystem includes:

* customer demographic data,
* loan origination data,
* repayment behavior,
* acquisition channels,
* behavioral risk signals,
* and portfolio outcome metrics.

## Portfolio Coverage

* Personal Loans
* SME Working Capital Loans
* Buy Now Pay Later (BNPL)

## Key Variables Included

### Customer Profile

* Geography
* Employment Type
* Income Proxy
* Bureau Score
* Thin File Indicator

### Loan Attributes

* Loan Amount
* Product Type
* Tenure
* Interest Rate
* Origination Risk Grade

### Repayment Behavior

* Days Past Due (DPD)
* Missed Payments
* Partial Payments
* Delinquency Buckets

### Behavioral Signals

* Balance Volatility
* Spending Shock
* Cash Flow Consistency
* EMI-to-Income Ratio

### Business Metrics

* Acquisition Cost
* Customer Lifetime Value
* Risk-Adjusted Return
* Net Revenue

---

# Methodology

## 1. Synthetic Data Generation

A synthetic digital lending portfolio was created to simulate customer acquisition, underwriting, loan servicing, and repayment behavior.

## 2. Feature Engineering

Additional behavioral and financial indicators were engineered, including:

* repayment ratio,
* balance volatility,
* stress indicators,
* delinquency transitions,
* and affordability measures.

## 3. Portfolio Analytics

The portfolio was analyzed across:

* customer segments,
* acquisition channels,
* loan products,
* and origination cohorts.

## 4. Risk Strategy Development

Insights were translated into actionable policy recommendations for:

* underwriting,
* pricing,
* acquisition optimization,
* and early warning monitoring.

---

# Key Analyses Performed

## Risk Segmentation

Customers were segmented into risk tiers using:

* bureau quality,
* income stability,
* repayment behavior,
* and behavioral stress indicators.

## Vintage / Cohort Analysis

Origination cohorts were evaluated to identify deterioration trends and channel-driven portfolio quality shifts.

## Acquisition Channel Analysis

Compared:

* CAC,
* default rates,
* profitability,
* and long-term portfolio performance across channels.

## Product Performance Analysis

Evaluated risk-return tradeoffs across:

* Personal Loans,
* SME Loans,
* and BNPL products.

## Early Warning System (EWS)

Designed a three-trigger watchlist framework using:

* DPD movement,
* balance volatility,
* and EMI stress indicators.

---

# Key Findings

* Aggressive acquisition through DSA and Digital Ads channels contributed disproportionately to rising delinquency rates.
* Behavioral indicators such as balance volatility and repayment ratio were stronger delinquency predictors than static demographic variables.
* SME loans generated stronger long-term profitability despite moderate default rates.
* BNPL customers showed elevated risk but potential strategic value as future cross-sell candidates.
* Customers with high EMI-to-income ratios demonstrated materially higher transition rates into delinquency buckets.

---

# Policy Recommendations

## 1. Tighten DSA Underwriting

* Introduce near-prime score floors
* Cap exposure for higher-risk applicants
* Reduce sub-prime originations

## 2. Implement Risk-Based Pricing

* Reward low-risk borrowers with lower pricing
* Increase pricing for higher expected-loss segments

## 3. Deploy Behavioral Early Warning Framework

* Monitor customers with:

  * early DPD movement,
  * high balance volatility,
  * and elevated EMI stress
* Trigger proactive collections intervention

---

# Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook
* Power BI / Excel

---

# Repository Structure

```text
digital-lending-risk-analysis/
│
├── data/
│   ├── raw_synthetic_data.csv
│   └── enriched_portfolio_data.csv
│
├── notebooks/
│   ├── data_generation.ipynb
│   ├── feature_engineering.ipynb
│   └── portfolio_analysis.ipynb
│
├── reports/
│   ├── CRO_Credit_Policy_Report.pdf
│   └── presentation_deck.pdf
│
├── visuals/
│
├── README.md
│
└── requirements.txt
```

---

# Future Improvements

Potential future enhancements include:

* Probability of Default (PD) modeling
* Expected Credit Loss (ECL) framework
* Survival analysis for delinquency transitions
* Dynamic behavioral scoring
* Collections optimization simulation
* Scenario and stress testing

---

# Disclaimer

This project uses a synthetically generated dataset designed to simulate a realistic digital lending portfolio.
AI-assisted tools were used for drafting refinement, formatting support, and presentation enhancement.
All business framing, portfolio logic, analytical direction, and strategic recommendations were independently conceptualized and reviewed by the author.

---

# Author

Harsh Singh
Credit Risk & Portfolio Analytics Project
Summer Analytics Initiative | 2026
