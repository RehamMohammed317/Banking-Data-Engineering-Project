# 🏦 Banking Data Warehouse & Analytics Project

## Overview

End-to-end Banking Data Engineering and Analytics project focused on data cleaning, ETL pipelines, SQL Server Data Warehousing, Star Schema modeling, and interactive Power BI dashboards for financial and risk analysis.

---

# Architecture

```text
Raw Banking Data
        ↓
Python Data Cleaning
        ↓
SQL Server
        ↓
SSIS ETL Pipelines
        ↓
Star Schema Data Warehouse
        ↓
Power BI Dashboards
```

---

# Technology Stack

| Layer | Technologies |
|---|---|
| Data Processing | Python, Pandas |
| Data Warehouse | SQL Server |
| ETL | SSIS |
| Data Modeling | Star Schema |
| Visualization | Power BI |

---

# Data Warehouse Design

### Fact Table
- Fact_Client_Financials

### Dimension Tables
- Dim_Client
- Dim_Income_Band
- Dim_Risk
- Dim_Banking_Profile
- Dim_Date

---

# Power BI Dashboards

## Banking Performance Overview
![Overview Dashboard](project_screenshots/overview_dashboard.png)

---

## Customer Insights & Segmentation
![Customer Insights Dashboard](project_screenshots/customer_insights_dashboard.png)

---

## Risk Analysis Dashboard
![Risk Analysis Dashboard](project_screenshots/risk_analysis_dashboard.png)

---

# ETL & Data Warehouse Assets

## Banking Star Schema
![Banking Star Schema](project_screenshots/star_schema.png)

---

## SSIS Data Flow Pipeline
![SSIS Pipeline](project_screenshots/ssis_pipeline.png)

---

## SSIS Client ETL Pipeline
![SSIS Client ETL Pipeline](project_screenshots/ssis_client_etl_pipeline.png)

---

# Repository Structure

```text
Banking-Data-Engineering-Project/
│
├── data/
├── notebooks/
├── powerbi/
├── project_screenshots/
├── README.md
└── LICENSE
```

---

# Contributors

- Reham Mohammed
- Sara Abuzied
