# Engine Production AI Prompt Story Map

Use this prompt pack to run analysis step by step and build a clear narrative from data to decisions.

## How to Use

- Run one prompt at a time.
- Execute the generated code in your notebook.
- Keep only working code.
- Write a 1–2 sentence takeaway before moving to the next step.
- Reuse this suffix for every prompt:
  - Return: (1) Python code, (2) expected output description, (3) one-sentence interpretation, (4) next-step recommendation.

## Prompt 0: Analyst Mode

You are a manufacturing operations analyst. Use concise, reproducible pandas/seaborn/scipy code only. Avoid over-cleaning. Keep business interpretation practical for plant decisions.

## Prompt 1: Business Questions

Given this engine production dataset, propose 3 decision-focused questions: one for throughput, one for quality, one for downtime. For each, define the metric and why it matters operationally.

## Prompt 2: Data Trust Check

Profile data quality: missingness, duplicates, invalid numeric ranges, inconsistent categories, and timestamp issues. Propose minimal cleaning steps ranked by impact on analysis validity.

## Prompt 3: Baseline KPI Table

Create a compact KPI table with total production, total defects, defect rate, total downtime, average downtime per record, and any one efficiency metric you can justify from available columns.

## Prompt 4: Loss Concentration

Find where loss concentrates by Machine_ID, Shift, and Model_Type. Rank top/bottom groups by defect rate and average downtime, and include contribution share to total defects/downtime.

## Prompt 5: Story Visual 1 (Comparison)

Build one high-signal comparison chart for shifts (production vs defects) and explain what operational imbalance it reveals.

## Prompt 6: Story Visual 2 (Pattern Map)

Build one map-like pattern view (heatmap) of average downtime by Day_of_Week and Shift. Identify hotspots and suggest one likely operational cause per hotspot.

## Prompt 7: Statistical Check

Test whether downtime differs across shifts using an appropriate nonparametric test if needed. Report test choice, null hypothesis, statistic, p-value, and plain-English conclusion.

## Prompt 8: Decision Memo

Write a 6-bullet operations memo: key findings, highest-risk segment, likely root-cause hypotheses, one limitation, and top 3 prioritized actions with success metrics.

## Prompt 9: Executive Narrative

Turn all findings into a short story arc: What is happening → Where losses are concentrated → Why likely happening → What to do next this week vs this quarter.

## Optional Narrative Template

- We observed ___, which suggests ___, so the next question is ___.
- Evidence: [metric/chart]. Risk or uncertainty: ___. Decision: ___.
