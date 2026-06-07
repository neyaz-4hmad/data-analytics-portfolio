# CS2 — Restaurant Performance Analysis

## Business Problem
A restaurant chain needs to identify which outlets, menu categories, and day-parts generate the most revenue — and which are dragging down overall performance.

## Dataset
- Outlet-level sales data with menu category, day, time slot, revenue, and covers

## Key Findings
- Weekend evenings generated disproportionately high revenue per cover
- Certain menu categories had high order volume but low margin contribution
- Outlet-level variance showed 2–3 locations consistently underperforming the chain average

## Recommendations
- Focus promotional activity on high-margin menu items during peak day-parts
- Review staffing and portion costs at underperforming outlets
- Introduce weekday lunch specials to smooth revenue distribution

## Techniques Used
- `pivot_table` for outlet × category revenue breakdown
- `groupby` with time-based segmentation
- Bar and line charts for trend and comparison visualisation

## Score: 8.9 / 10
