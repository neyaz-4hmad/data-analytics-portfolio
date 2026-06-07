# CS9 — Logistics & Delivery Operations 🏆

## Business Problem
A logistics company is missing delivery SLAs on a growing share of shipments. Operations needs to identify which routes, hubs, and time windows are causing failures — and build a data-backed fix.

## Dataset
- Shipment records with origin hub, destination city, carrier, promised delivery date, actual delivery date, and weight

## Key Findings
- 3 origin hubs accounted for 68% of all SLA breaches despite handling average volumes
- Same-day and next-day shipments had a 4× higher breach rate than standard shipments
- Certain carrier + route combinations had a near-zero on-time record

## Recommendations
- Audit processes at the 3 highest-breach hubs — retrain or restructure dispatch teams
- Apply buffer time to same-day and next-day SLA commitments until hub performance improves
- Terminate or renegotiate contracts with consistently underperforming carrier routes

## Techniques Used
- Date arithmetic for SLA breach calculation and lead time analysis
- `groupby` + multi-level aggregation for hub and carrier performance tables
- `pct_change` for rolling breach rate trend tracking

## Score: 10.0 / 10 🏆
