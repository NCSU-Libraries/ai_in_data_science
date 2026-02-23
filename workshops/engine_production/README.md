# Workshop 02: Engine Production Analysis

This workshop analyzes hourly engine production operations data.

## Dataset
- File: `data/engine_production_data_original.csv`
- Main fields: `Timestamp`, `Shift`, `Day_of_Week`, `Machine_ID`, `Model_Type`, `Production_Count`, `Defective_Count`, `Downtime_Min`

## Notebook
- Template notebook: `engine_production_data.ipynb`
- Filled notebook: `engine_production_data_filled.ipynb`

## Workflow Design
1. Data loading and inspection
2. **Light data cleaning** (short section: day-label standardization, missing numeric handling, timestamp parsing)
3. EDA on production, defects, and downtime
4. One simple statistical check
5. Conclusions and operational recommendations

## Notes
- Cleaning is intentionally limited so the primary focus remains on analysis and interpretation.
