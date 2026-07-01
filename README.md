# Telecom_Churn_Risk_Analytics

Excel-based analysis of customer churn patterns across a telecom subscriber base, using PivotTables and an interactive dashboard to surface key churn drivers.

---

## Overview

This project analyzes a dataset of 4,250+ telecom customers to identify patterns and drivers behind customer churn. Using PivotTables and interactive charts, the analysis breaks down churn behavior by service plans, usage patterns, and customer service interactions to build a dashboard-style view of churn risk.

## Objective

To identify which customer attributes and usage behaviors are most associated with churn, enabling telecom providers to prioritize retention efforts on high-risk segments.

## Dataset

Customer-level data including:

| Category | Fields |
|---|---|
| Identifiers | State, Area Code |
| Tenure | Account Length |
| Plans | International Plan, Voice Mail Plan |
| Usage | Day / Evening / Night / International minutes, calls, and charges |
| Service | Number of Customer Service Calls |
| Target | Churn (Yes / No) |

## Approach

1. **Data Preparation** — Cleaned and structured raw customer records (~4,250 rows) for pivot-based analysis
2. **PivotTables** — Built 6 PivotTables summarizing churn rate, plan adoption, usage volumes, and average charges across customer segments
3. **Service Friction Analysis** — Analyzed customer service call frequency by area code to flag high-friction regions
4. **Dashboard Design** — Designed a 12-chart interactive dashboard visualizing churn distribution, plan usage, and usage patterns
5. **Churn Driver Analysis** — Cross-referenced churn rate against plan type and usage metrics to surface key churn indicators

## Key Findings

- **Overall churn rate:** ~14% (598 of 4,250 customers)
- **International plan subscribers** show disproportionately higher churn, despite being a small subscriber base (396 customers)
- **Customer service call volume** varies notably by area code, indicating region-specific service friction
- **Usage charges** (day/evening/night/international) show measurable variation between churned and retained customers

## Tools Used

- Microsoft Excel
  - PivotTables
  - PivotCharts
  - Dashboard Design

## File

`Telecom_ChurnRisk_Analytics.xlsx`

---

*This project was built as an independent data analysis exercise using a publicly available telecom churn dataset.*
