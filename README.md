<a name="top"></a>

<div align="center">

# 📊 Financial Health Dashboard

### Power BI Internship Project — CodeAlpha

*Transforming raw business data into meaningful financial and performance insights.*

<p>
  <img alt="Power BI" src="https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black">
  <img alt="DAX" src="https://img.shields.io/badge/DAX-217346?style=flat&logo=microsoft&logoColor=white">
  <img alt="Power Query" src="https://img.shields.io/badge/Power%20Query-004B87?style=flat&logo=powerquery&logoColor=white">
  <img alt="Data Modeling" src="https://img.shields.io/badge/Data%20Modeling-0078D4?style=flat&logo=microsoft&logoColor=white">
</p>

</div>

---

## 📑 Table of Contents

- [Project Overview](#-project-overview)
- [Dataset Overview](#-dataset-overview)
- [Business Objectives](#-business-objectives)
- [Key KPIs](#-key-kpis)
- [Analytics Workflow](#-analytics-workflow)
- [Data Cleaning & Transformation](#-data-cleaning--transformation)
- [Data Modeling](#-data-modeling)
- [Dashboard Pages](#-dashboard-pages)
- [Key Insights](#-key-insights)
- [Business Recommendations](#-business-recommendations)
- [Analytical Features](#-analytical-features)
- [Tools & Skills](#-tools--skills)
- [Project Files](#-project-files)
- [Project Video](#-project-video)
- [Internship](#-internship)
- [Author](#-author)

---



## 📌 Project Overview

The **Financial Health Dashboard** is an interactive Power BI project developed as part of the **CodeAlpha Power BI Internship**.

The project transforms raw business and sales data into meaningful financial and business insights through **data cleaning, data modeling, DAX calculations, financial analysis, business performance analysis, and interactive data visualization**.

The dashboard provides a comprehensive view of the business across **revenue, profitability, financial health, cash flow, customer and product performance, regional performance, and future trends**.

The project follows a complete data analysis workflow, from preparing and transforming the raw data to building an interactive dashboard that supports data-driven business decisions.

---
## 🗃️ Dataset Overview

The project is based on a large sales and business dataset containing **200,000+ records**.

The dataset includes information about orders, customers, products, locations, sales, revenue, and profit, providing the foundation for financial and business performance analysis.

| Attribute | Details |
| --- | --- |
| **Format** | CSV |
| **Records** | 200,000+ |
| **Main Data** | Orders, Customers, Products, Sales & Financial Performance |

### Main Columns

| Category | Columns |
| --- | --- |
| 🧾 **Orders** | `Order_ID`, `Order_Date` |
| 👤 **Customers** | `Customer_Name` |
| 🌍 **Location** | `City`, `State`, `Region`, `Country` |
| 📦 **Products** | `Category`, `Sub_Category`, `Product_Name` |
| 💰 **Sales** | `Quantity`, `Unit_Price`, `Revenue`, `Profit` |

---
## 🎯 Business Objectives

The dashboard was designed to provide a clear view of the company's financial and business performance and answer key analytical questions:

- How is **revenue and profitability** performing?
- What is the company's overall **financial health**?
- How are **COGS, operating expenses, and net profit** affecting financial performance?
- How is the company's **cash flow** performing?
- Which **products and categories** contribute most to revenue and profit?
- How does performance vary across different **regions**?
- How does **customer performance** contribute to overall revenue?
- How does **business performance** change over time?
- What are the expected **future revenue and profit trends** based on forecasting?

---
## 📊 Key KPIs

The dashboard uses a set of financial and business KPIs to monitor overall performance and support data-driven analysis.

### 💰 Financial KPIs

- **Total Revenue**
- **Net Profit**
- **Profit Margin %**
- **Gross Profit**
- **COGS**
- **Operating Expenses**
- **Current Ratio**
- **Debt to Equity**
- **ROA (Return on Assets)**
- **ROE (Return on Equity)**
- **Net Cash Flow**
- **Operating Cash Flow Margin %**

### 📈 Business KPIs

- **Total Orders**
- **Total Quantity**
- **Average Order Value**
- **Total Customers**
- **Total Products**

### 🔮 Forecasting KPIs

- **Forecast Revenue**
- **Forecast Profit**

---
## 🔄 Analytics Workflow

The project follows a structured data analytics workflow from raw data preparation to business insights.

```mermaid
flowchart LR
    A["📊 Raw Data"] --> B["🧹 Data Cleaning"]
    B --> C["🗂️ Data Modeling"]
    C --> D["🧮 DAX Analysis"]
    D --> E["📈 Visualization"]
    E --> F["💡 Insights"]
```

### Workflow Stages

| Stage | Description |
| --- | --- |
| 📊 **Raw Data** | Imported the original sales and business data. |
| 🧹 **Data Cleaning** | Cleaned and transformed the data using Power Query. |
| 🗂️ **Data Modeling** | Created the required tables and relationships for analysis. |
| 🧮 **DAX Analysis** | Developed measures and KPIs for financial and business analysis. |
| 📈 **Visualization** | Built interactive Power BI reports and dashboards. |
| 💡 **Insights** | Identified financial and business performance insights. |

---
## 🧹 Data Cleaning & Transformation

Data preparation and transformation were performed using **Power Query**.

The main cleaning steps included:

1. **Changed Data Types**
   - Updated the data types of `Order_ID` and `Order_Date`.

2. **Removed Name Titles**
   - Removed titles appearing at the beginning of customer names:
   - `Mr.`, `Mrs.`, `Ms.`, `Miss`, `Dr.`

3. **Trimmed Text**
   - Removed unnecessary spaces from text values.

4. **Removed Name Suffixes**
   - Removed suffixes appearing at the end of customer names:
   - `MD`, `DDS`, `PhD`, `DVM`

5. **Trimmed Text**
   - Applied text trimming again after removing suffixes.

6. **Cleaned Text**
   - Applied text cleaning to standardize text values.

7. **Created Gender Column**
   - Added a new `Gender` column for customer analysis.

---
## 🗂️ Data Modeling

The data model was designed in Power BI to support financial and business performance analysis.

### Tables

- **Main Sales Dataset** — Contains the main sales, customer, product, and business data.
- **Financials** — Contains the financial data used for financial statement analysis.
- **Calendar** — Date table used for time-based analysis and forecasting.

### Relationships

- Created relationships between the **Calendar** table and the relevant date fields.
- Connected the **Main Sales Dataset** and **Financials** data with the Calendar table to support consistent time-based analysis.

### DAX Measures

Created DAX measures for:

- Financial KPIs
- Business KPIs
- Profitability analysis
- Cash flow analysis
- Customer and product analysis
- Forecasting

The model was structured to support interactive filtering, cross-filtering, and time-based analysis across the dashboard pages.

---
