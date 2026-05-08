# 🏦 Banking Data Warehouse & Analytics Project

## 📌 Project Overview
This project is an end-to-end data engineering and business intelligence solution built on a banking dataset. It covers data cleaning, data modeling, ETL pipeline development, and interactive dashboards to extract insights about customer behavior, financial performance, and risk analysis.

The project demonstrates a full data lifecycle from raw CSV data to a structured Data Warehouse and finally to interactive Power BI dashboards.

---

## 🧠 Project Objectives
- Clean and preprocess raw banking data using Python (Pandas)
- Perform exploratory data analysis (EDA) and visualization
- Load cleaned data into SQL Server (SSMS)
- Design a Star Schema Data Warehouse
- Build ETL pipelines using SSIS
- Develop interactive Power BI dashboards for business insights

---

## 🛠️ Technologies Used
- Python (Pandas, Data Cleaning, EDA)
- SQL Server (SSMS)
- SSIS (ETL Pipelines)
- Power BI (Data Visualization)
- Excel / CSV

---

## 🧹 Data Cleaning (Python)
- Handled missing values
- Removed duplicates
- Standardized categorical values
- Converted data types
- Exported cleaned dataset as CSV

---

## 🗄️ Data Warehouse Design (Star Schema)

The data warehouse follows a **Star Schema architecture**:

### Fact Table:
- Fact_Client_Financials

### Dimension Tables:
- Dim_Client
- Dim_Income_Band
- Dim_Risk
- Dim_Banking_Profile
- Dim_Date

This structure enables efficient analytical queries and reporting.

---

## 🔄 ETL Process (SSIS)
- Extract data from cleaned CSV files
- Transform data using lookup and mapping logic
- Load data into Fact and Dimension tables
- Implemented surrogate keys for all dimensions
- Ensured data consistency and prevented duplication

---

## 📊 Power BI Dashboards

### 1. Banking Overview Dashboard
- Total Clients
- Total Deposits
- Total Loans
- Banking account distribution
- Filters by Year and Gender

### 2. Customer Segmentation Dashboard
- Income Band analysis
- Gender distribution
- Occupation insights
- Loyalty classification
- Fee structure segmentation

### 3. Risk & Financial Behavior Dashboard
- Risk weighting analysis
- Loans vs Income comparison
- Credit card balance insights
- High-risk customer identification

---

## 📈 Key Insights
- Customer income strongly influences banking product usage
- High-income clients are not always low-risk
- Loans and deposits patterns vary across customer segments
- Risk levels are distributed across all income bands

---

## 📷 Project Screenshots

### 📊 Bank Performance Overview
![Bank Dashboard](Project%20screenshots/Bank%20performance%20overview.png)

### 👥 Client Insights Dashboard
![Client Insights](Project%20screenshots/clients%20insights.png)

### ⚠️ Risk Analysis Dashboard
![Risk Dashboard](Project%20screenshots/Risk.png)

---

## ⚙️ ETL & Architecture

### Star Schema Design
![Star Schema](Project%20screenshots/star%20schema.png)

### SSIS Pipeline
![SSIS Pipeline](Project%20screenshots/ssis%20pipline.png)
---

## 🚀 Project Highlights
- End-to-end Data Engineering pipeline
- Real-world banking analytics scenario
- Scalable Data Warehouse design
- Interactive dashboards for decision making

---

## 📌 Author
Data Engineering & Analytics Project
