# Saudi Superstore Sales Intelligence System

End-to-end Business Intelligence pipeline covering descriptive, predictive, and
prescriptive analytics for the Saudi Superstore retail dataset (2011–2014).

## Overview
- **Descriptive (Power BI):** Interactive dashboard analyzing sales and profit
  across Saudi cities, product categories, and customer segments, with dynamic
  filtering by date, city, and category.
- **Predictive (Altair AI Studio):** Linear Regression model forecasting sales
  revenue from quantity, shipping cost, category, and segment.
- **Prescriptive:** Rule-based decision tree translating both models' outputs
  into concrete business recommendations (inventory, marketing, logistics).

## Key Results
| Metric | Value |
|---|---|
| Predictive Model R² | 0.831 |
| RMSE | 463.357 SAR |
| Top City | Riyadh — 33,035 SAR in sales |
| Top Category | Technology |

## Key Findings
- Riyadh and the Technology category are the dual pillars of store performance.
- The Home Office segment represents only 21.76% of the market — a significant
  untapped growth opportunity.
- The Discount attribute was entirely unused (all zero values) — an untested
  pricing lever identified for future experimentation.

## Tools
Power BI, Altair AI Studio (RapidMiner), Linear Regression

## Report
See `Final_Report_Project_DB2.docx` for the full write-up, including dashboard
screenshots, model workflow, and the full prescriptive decision framework.
