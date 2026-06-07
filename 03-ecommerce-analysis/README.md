# CS3 — E-Commerce Order Analysis

## Business Problem
An e-commerce platform wants to reduce cart abandonment, improve delivery times, and understand which customer segments and product categories drive repeat purchases.

## Dataset
- Orders with customer ID, product category, order status, payment method, delivery date, and revenue

## Key Findings
- Delivery delays were concentrated in 2 specific regions, accounting for 60%+ of late orders
- Repeat purchase rate was 3× higher among customers who received orders within 3 days
- COD (cash on delivery) orders had significantly higher return and cancellation rates

## Recommendations
- Partner with additional logistics providers in high-delay regions
- Set up fast-delivery corridors for top customer segments to improve retention
- Incentivise prepaid payment methods to reduce returns and cancellations

## Techniques Used
- Date arithmetic for delivery SLA calculation
- `groupby` + `pct_change` for trend tracking
- `numpy.where` for flag columns (late / on-time, repeat / new)

## Score: 9.7 / 10
