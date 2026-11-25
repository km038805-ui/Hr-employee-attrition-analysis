# HR Employee Attrition Analysis — Portfolio Practice Project

**By:** Muhammad K. — Data Analyst in progress, Madinah, Saudi Arabia
**GitHub:** https://github.com/km038805-ui
**Skills used:** Excel, Google Sheets, Python, Pandas, Data Cleaning, Data Analysis

> Portfolio practice project. This is **not client work and not work for any employer**.
> The data is public Kaggle data, analysed as practice. The employees in this data are **fictional** — IBM created it as sample data, so no finding here is about any real person or real company.

## Data source
- **Kaggle dataset:** IBM HR Analytics Employee Attrition & Performance — https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset
- **File:** `WA_Fn-UseC_-HR-Employee-Attrition.csv` — 1470 employees, 35 columns.
- **Download mirror used (no Kaggle login needed):** https://github.com/shreyash04/IBM-HR-Analytics
- **Licence / use:** IBM sample data, redistributed for learning and analysis.

## What I cleaned
- Dropped 3 constant columns that carry no information (`EmployeeCount`, `Over18`, `StandardHours`).
- Checked duplicates: **0 removed**; missing values: **0**.
- Saved the cleaned file as `hr_attrition_cleaned.csv` and `hr_attrition_cleaned.xlsx`.

## Key findings (real numbers from the data)
- Overall attrition: **237 of 1470 employees left — 16.12%**.
- Attrition by department: Sales **20.63%**, Human Resources **19.05%**, Research & Development **13.84%**.
- **Overtime is the strongest signal:** employees who worked overtime left at **30.53%**, vs **10.44%** for those who did not.
- Highest attrition job role: Sales Representative **39.76%**, then Laboratory Technician **23.94%**; lowest: Research Director **2.5%** and Manager **4.9%**.
- Low job satisfaction (1 out of 4) left at **22.84%**, high satisfaction (4) at **11.33%**.
- Average monthly income: left **$4,787.09**, stayed **$6,832.74**.
- Average years at the company: left **5.13 years**, stayed **7.37 years**.
- Average age: **36.92 years**.

## Files
- `hr_attrition_cleaned.csv` / `.xlsx` — cleaned data + Excel summaries
- `analysis.py` — Python/Pandas cleaning and analysis
- `charts/` — attrition by department, by overtime, by job satisfaction
- `findings.json` — all numbers above, computed by the script

## What a business can learn from this
Overtime, low pay and low satisfaction go together with leaving. Reducing overtime in Sales and for Sales Representatives, and checking pay and satisfaction for the lowest-paid staff, would be the first places to look.

> The cleaned Excel workbook (.xlsx) and chart images are in the local portfolio / CV, not in this repo, because this upload contains text files only.
