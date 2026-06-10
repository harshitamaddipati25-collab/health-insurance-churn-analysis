# Health Insurance Mid-Year Churn Analysis

## The Question
Why do Americans drop their health insurance mid-year — and where should insurers intervene?

## Key Findings
- National average mid-year churn rate: **21.76%**
- West Virginia, Arkansas, and Texas have the highest churn — up to **1.4x the national average**
- States with lower median income show significantly higher churn rates
- Churn is getting worse — spiked from 20.65% in 2022 to **23.64% in 2024**

## Business Recommendation
Insurers should focus proactive outreach in Q2 targeting low-income enrollees in high-churn Southern states before the Q3 spike.

## Tools Used
- **Python** (Pandas, NumPy) — data cleaning, EDA, churn calculation
- **Snowflake** — cloud data warehouse, SQL transformations
- **Power BI** — live dashboard connected to Snowflake
- **Data Sources** — CMS Marketplace Public Use Files, Census ACS S1901

## Dashboard
![Dashboard](dashboard_screenshot.png)

## Project Structure
- `01_eda.ipynb` — Python notebook with full analysis
- `churn_final.csv` — cleaned dataset
