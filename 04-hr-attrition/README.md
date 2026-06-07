# CS4 — HR Attrition Analysis

## Business Problem
A company is losing experienced staff at an above-average rate. HR needs to identify which departments, salary bands, and employee profiles carry the highest attrition risk — and act before talent walks out the door.

## Dataset
- Employee records with department, tenure, salary band, performance rating, and attrition flag

## Key Findings
- Employees with 1–3 years of tenure in mid-salary bands had the highest attrition rate
- Two departments accounted for over 50% of total exits despite being mid-sized
- High performers leaving in year 2 indicated a recognition and growth gap

## Recommendations
- Introduce structured career progression milestones at the 18-month mark
- Conduct stay interviews in the two highest-attrition departments immediately
- Review compensation bands for mid-level employees against market benchmarks

## Techniques Used
- `numpy.select` for multi-condition risk scoring
- `groupby` for department and band-level attrition rates
- Horizontal bar charts for comparative severity visualisation

## Score: 9.8 / 10
