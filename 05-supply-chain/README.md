# CS5 — Supply Chain & Inventory Analysis 🏆

## Business Problem
A manufacturing company is experiencing stockouts on fast-moving items while overstocking slow-moving ones — tying up working capital and causing lost sales simultaneously.

## Dataset
- SKU-level inventory data with reorder points, lead times, demand rates, and carrying costs

## Key Findings
- 18% of SKUs were responsible for 74% of total stockout incidents
- Slow-moving items were holding 3× more stock than required based on demand patterns
- Reorder points had not been recalibrated in over 12 months, misaligning with current demand

## Recommendations
- Recalculate reorder points for top 20% SKUs based on current 90-day demand data
- Liquidate or return bottom-velocity SKUs to free up warehouse space and working capital
- Implement weekly demand review cycle for high-impact categories

## Techniques Used
- IQR-based outlier detection for demand anomalies
- Feature engineering for reorder flag and safety stock columns
- `matplotlib` subplots for inventory position vs. demand overlay

## Score: 10.0 / 10 🏆
