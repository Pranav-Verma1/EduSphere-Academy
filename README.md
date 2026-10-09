# EduSphere Academy

Power BI portfolio project for a fictional coaching institute. Built June–July 2025.

Five years of enrollments, course fees, trainers, and marketing spend are modelled as a star schema and reported in an 8-page dashboard: where revenue grows, which courses and trainers are profitable, and which admission channels return the spend.

EduSphere Academy is not a real client.

## What is in this repo

- `Coaching_Institute_Portfolio.pdf` — the write-up
- `EduSphere-Academy-Dashboard.pbix` — the Power BI report
- `logo.png` — project mark
- `data/EduSphere_Sample_Data.xlsx` — the source workbook

## Model

- One fact table, `Output`, with one row per enrollment (349 rows)
- 12 dimension tables, joined many-to-one
- 15+ DAX measures for revenue, cost, gross profit, completion, and marketing ROI

## Headline figures

- ?2.52M fee revenue
- 349 enrollments
- 21.5% gross margin
- 36 courses and 16 trainers

Stack: Excel, Power Query, Power BI, DAX.
