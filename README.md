# Chicago Food Inspections Analysis

An end-to-end data analytics project exploring food inspection outcomes in Chicago from 2010 to 2019 using Python and Power BI.

## Project Overview

This project analyzes inspection results, failure rates, facility categories, recurring violations and ZIP code patterns.

**Tools:** Python, pandas, Jupyter Notebook, Power BI, Power Query, DAX

**Dataset:** 196,825 original records across 22 columns; 196,676 cleaned records across 16 columns.

## Workflow

### 1. Python Data Preparation

The Jupyter Notebook documents the data inspection, cleaning, exploratory analysis and preparation of the cleaned dataset.

See [Python analysis notebook](Jupyter%20notebook/Chicago_Food_Inspection_Analysis.ipynb) for the executed code, Markdown explanations and outputs.

### 2. Power BI Dashboard

The dashboard contains:

- KPI cards for inspection totals and failure rates.
- Inspection outcome distribution.
- Annual failure-rate trend.
- Top 5 facility types by failed inspections.
- Top 5 violations summary.
- Chicago ZIP code Shape Map.
- Interactive slicers for Year, Facility Type, Risk and Results.

## Key Results

| Metric | Value |
|---|---:|
| Total Inspections | 196,676 |
| Completed Inspections | 171,470 |
| Failed Inspections | 38,055 |
| Failure Rate | 22.19% |

Restaurants recorded the highest number of failed inspections (24,452), followed by grocery stores (5,923) and schools (2,381).

## Project Files

- [Python Jupyter Notebook](Jupyter%20notebook/Chicago_Food_Inspection_Analysis.ipynb) — Cleaning and exploratory analysis.
- [Raw Dataset (.7z)](data/raw/Chicago_Food_Inspections_Raw.7z) — Original inspection data.
- [Cleaned Dataset (.7z)](data/cleaned/Chicago_Food_Inspections_Cleaned.7z) — Processed inspection data.
- [Power BI Report (.pbix)](dashboard/Chicago_Food_Inspection_Report.pbix) — Interactive dashboard and data model.
- [Dashboard Screenshot](dashboard/Chicago%20Food%20Inspection%20dashboard%20screenshot.png) — Dashboard preview.

## Important Notes

- Failure rate is calculated as failed inspections divided by completed inspections.
- The Top 5 Violations summary is static and does not respond to slicers.
- ZIP code failure counts show recorded inspection volume, not a geographic failure rate or measure of neighborhood safety.
- The dataset covers 2010–2019 and should not be interpreted as current inspection conditions.

## Dashboard Preview

![Chicago Food Inspections Dashboard](dashboard/Chicago%20Food%20Inspection%20dashboard%20screenshot.png)

## Detailed Project Case Study

[Read the Chicago Food Inspections Case Study on Notion](https://torpid-smell-609.notion.site/Chicago-Food-Inspections-Python-Power-BI-40a4c1fc422a80009c87f4e1c8526e0b)
