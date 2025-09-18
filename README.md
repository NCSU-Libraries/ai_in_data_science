# Emergency Room Wait Time Dataset (Class Use)

Source (original dataset): https://www.kaggle.com/datasets/rivalytics/er-wait-time?resource=download

This repository contains a copy of the ER Wait Time dataset for classroom/educational use. For a narrative overview and data dictionary, see [data/ER Wait Time Data Overview.txt](data/ER%20Wait%20Time%20Data%20Overview.txt).

## Files

- CSV: [data/ER Wait Time Dataset.csv](data/ER%20Wait%20Time%20Dataset.csv)
- Excel: [data/ER Wait Time Dataset.xlsx](data/ER%20Wait%20Time%20Dataset.xlsx)
- Overview: [data/ER Wait Time Data Overview.txt](data/ER%20Wait%20Time%20Data%20Overview.txt)

## Dataset overview

- Rows: ~5,000 simulated ER visits
- Columns: ~20 features (hospital details, visit timing, urgency, wait components, outcomes, satisfaction)
- Timeframe: 2024 (simulated)

Example key fields:
- Visit/Patient/Hospital identifiers
- Region, Season, Day of Week, Time of Day
- Urgency Level (Critical, High, Medium, Low)
- Nurse-to-Patient Ratio, Specialist Availability, Facility Size (Beds)
- Time to Registration/Triage/Medical Professional (min), Total Wait Time (min)
- Patient Outcome (Admitted/Discharged/LWBS), Patient Satisfaction (1–5)

See the full descriptions in [data/ER Wait Time Data Overview.txt](data/ER%20Wait%20Time%20Data%20Overview.txt).

## Quick start

Python (pandas):
```python
import pandas as pd

df = pd.read_csv("data/ER Wait Time Dataset.csv", parse_dates=["Visit Date"])
# Basic peek
print(df.head())
print(df.describe(include="all"))