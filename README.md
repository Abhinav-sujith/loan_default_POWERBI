# 📊 Loan Default Risk Analysis Dashboard – Power BI

This project presents an in-depth **Loan Default Risk Analysis** using Power BI, backed by a well-structured data model created via **Microsoft SQL Server** and **Power BI Dataflows**. The goal is to help financial institutions **identify borrower risk**, analyze **default patterns**, and make **data-driven lending decisions**.

## 📁 Project Structure

- `Page 1 – Overview`: Macro-level loan and default trends across age groups, employment types, and time.
- `Page 2 – Applicant Details`: Demographic and credit score breakdown of applicants with disbursed loans.
- `Page 3 – Risk Metrics`: YOY analysis of loan amounts and default volume segmented by income and employment.

## 💡 Key Insights

- Adults aged 20–30 have the highest average loan amounts.
- Default rates peaked in 2016 and are highest among the unemployed.
- Home and business loans make up the majority of the portfolio.
- Bachelors degree holders account for the most loans.
- Medium credit score range (450–650) in adults sees the highest loan amounts.
- YOY loan amounts and default rates show significant volatility, with sharp increases and decreases between 2014 and 2018.
- High-income, full-time employees account for the largest loan amounts, but part-time and self-employed segments also represent substantial risk.

## 🔧 Tools & Technologies

| Tool                | Purpose                             |
|---------------------|--------------------------------------|
| Power BI Desktop     | Interactive dashboard & reporting   |
| Power BI Dataflows   | ETL logic, transformations, refresh |
| Microsoft SQL Server | Primary data source                 |
| DAX                  | Measures for dynamic metrics & KPIs |

# Technical Workflow
Data Integration: Raw data loaded into Microsoft SQL Server for scalable storage and querying.
Dataflow Creation: Built a Power BI Dataflow to extract and transform data from SQL Server.

# Why Dataflows?

- Centralizes data prep and transformation.
- Enables dataset reuse across multiple reports.
- Supports data governance and version control.
- Scheduled & Incremental Refresh:
- Scheduled refresh keeps dashboards up-to-date.
- Incremental refresh optimizes performance by only processing new/changed data.

# Power BI Desktop Modeling:

- Imported dataflow into Power BI Desktop.
- Applied advanced DAX for YOY calculations, segmentation, and dynamic metrics.
- Visualization: Created interactive dashboards for deep analysis and stakeholder exploration.

## ✅ Recommendations Based on Analysis
- Tighten lending criteria for unemployed applicants and adults aged 20–30.
- Closely monitor medium credit score segments (450–650) due to high exposure.
- Diversify loan purposes to reduce concentration risk in home and business sectors.

# 📈 Skills Demonstrated
- Data engineering with Microsoft SQL Server
- ETL and data modeling using Power BI Dataflows
- Advanced DAX for financial analytics
- Interactive dashboard design and storytelling
- Automated data refresh and performance optimization
