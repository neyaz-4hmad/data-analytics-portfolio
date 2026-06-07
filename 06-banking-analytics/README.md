# CS6 — Banking & Customer Analytics

## Business Problem
A retail bank wants to reduce customer churn, improve product cross-sell, and identify which customer segments are most valuable — before competitors poach them.

## Dataset
- Customer records with account type, tenure, product holdings, transaction frequency, balance, and churn flag

## Key Findings
- Customers holding only one product churned at 4× the rate of multi-product customers
- High-balance customers with low transaction frequency showed early churn signals
- 25–35 age segment had the highest cross-sell acceptance rates

## Recommendations
- Launch targeted cross-sell campaign for single-product customers within 6 months of onboarding
- Assign relationship managers to high-balance, low-activity accounts as a retention measure
- Direct digital product promotions at 25–35 segment where conversion is highest

## Techniques Used
- Correlation analysis for churn signal identification
- `groupby` + multi-level aggregation for segment profiling
- `twinx` dual-axis charts for balance vs. activity visualisation

## Score: 9.9 / 10
