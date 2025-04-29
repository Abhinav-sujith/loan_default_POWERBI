## Loan Default Risk Analysis – Power BI Project

Welcome to the Loan Default Risk Analysis project! This repository showcases an end-to-end analytics solution for identifying and visualizing key risk metrics in loan portfolios. The project leverages Microsoft SQL Server, Power BI Dataflows, advanced DAX, and interactive dashboards to provide actionable insights for financial risk management.

## Project Structure
# The Power BI report is organized into three main pages:
- Loan Default Overview: Summary of loan volumes, average amounts, default rates by employment type, loan purpose, and age group.
Applicant Demographics & Financial Profile: This section examines borrower characteristics, including education, credit score, age, and marital status, and their impact on loan amounts and volumes.
- Financial Risk Metrics: Year-over-year (YOY) analysis of loan amounts and defaults, plus breakdowns by credit score, marital status, income bracket, and employment type.

# Key Findings
- Adults aged 20–30 have the highest average loan amounts.
- Default rates peaked in 2016 and are highest among the unemployed.
- Home and business loans make up the majority of the portfolio.
- Bachelors degree holders account for the most loans.
- Medium credit score range (450–650) in adults sees the highest loan amounts.
- YOY loan amounts and default rates show significant volatility, with sharp increases and decreases between 2014 and 2018.
- High-income, full-time employees account for the largest loan amounts, but part-time and self-employed segments also represent substantial risk.

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

# Recommendations Based on Analysis
- Tighten lending criteria for unemployed applicants and adults aged 20–30.
- Closely monitor medium credit score segments (450–650) due to high exposure.
- Diversify loan purposes to reduce concentration risk in home and business sectors.
- Use dataflows for scalable, maintainable ETL pipelines and ensure incremental refresh for large datasets.

# Skills Demonstrated
- Data engineering with Microsoft SQL Server
- ETL and data modeling using Power BI Dataflows
- Advanced DAX for financial analytics
- Interactive dashboard design and storytelling
- Automated data refresh and performance optimization
