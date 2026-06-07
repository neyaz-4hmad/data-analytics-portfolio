# CS7 — Hospital Operations Analysis

## Business Problem
A hospital group needs to optimise bed utilisation, reduce patient wait times, and identify which departments are operating beyond safe capacity — without increasing headcount.

## Dataset
- Patient records with department, admission date, discharge date, bed type, and wait time

## Key Findings
- Emergency and orthopaedic departments were running at 95%+ bed occupancy during weekday peaks
- Average wait time in 3 departments exceeded the hospital's own SLA by more than 40 minutes
- Discharge bottlenecks in the afternoon slot were creating artificial capacity crunches

## Recommendations
- Introduce staggered discharge protocols to free beds by 11am instead of 2pm
- Add surge capacity planning for emergency department on Monday and Tuesday peaks
- Review staffing ratios in the 3 SLA-breaching departments against patient volume data

## Techniques Used
- Date arithmetic for length-of-stay and wait time calculation
- `numpy.select` for occupancy risk flagging (normal / high / critical)
- Rolling averages for occupancy trend smoothing

## Score: 9.9 / 10
