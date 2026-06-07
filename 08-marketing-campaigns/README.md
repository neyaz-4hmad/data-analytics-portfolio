# CS8 — Marketing Campaign Analytics

## Business Problem
A consumer brand is running campaigns across 4 channels — email, social, paid search, and display — but has no clear picture of which channels are delivering ROI and which are burning budget.

## Dataset
- Campaign records with channel, spend, impressions, clicks, conversions, and revenue generated

## Key Findings
- Email and paid search delivered 3× higher conversion rates than display advertising
- Social campaigns had high engagement but below-average revenue per conversion
- Two campaign types were generating negative ROI when full cost attribution was applied

## Recommendations
- Reallocate 30% of display budget to email and paid search immediately
- Redesign social campaigns with a direct-response CTA to improve conversion quality
- Discontinue the 2 negative-ROI campaign types and reinvest in proven formats

## Techniques Used
- ROI and cost-per-conversion feature engineering
- `pivot_table` for channel × campaign type performance matrix
- Multi-series bar charts for spend vs. revenue comparison

## Score: 9.8 / 10
