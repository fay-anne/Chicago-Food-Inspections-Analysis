# Chicago Food Inspections Analysis

An end-to-end data analytics project exploring food inspection outcomes in Chicago from 2010 to 2019 using Python and Power BI.

## Project Overview

This project analyzes inspection results, failure rates, facility categories, recurring violations and ZIP code patterns.

**Tools:** Python, pandas, Jupyter Notebook, Power BI, Power Query, DAX

**Dataset:** 196,825 original records across 22 columns; 196,676 cleaned records across 16 columns.

## Workflow

### 1. Python Data Preparation

The Jupyter Notebook documents the data inspection, cleaning, exploratory analysis and preparation of the cleaned dataset.

See `Chicago_Food_Inspection_Analysis.ipynb` for the executed code, Markdown explanations and outputs.

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

- `Chicago_Food_Inspection_Analysis.ipynb` — Python cleaning and exploratory analysis.
- `Chicago_Food_Inspections_Cleaned.csv` — Cleaned inspection dataset.
- Power BI `.pbix` file — Final interactive dashboard.
- Chicago ZIP code TopoJSON — Geographic boundaries used in the Shape Map.
- Top 5 Violations summary — Overall violation counts used in Power BI.

## Important Notes

- Failure rate is calculated as failed inspections divided by completed inspections.
- The Top 5 Violations summary is static and does not respond to slicers.
- ZIP code failure counts show recorded inspection volume, not a geographic failure rate or measure of neighborhood safety.
- The dataset covers 2010–2019 and should not be interpreted as current inspection conditions.

## Dashboard Preview

[Insert final dashboard screenshot]

## Portfolio

[Insert Notion case study link]
