# Business Insights 360 - Power BI Project

[![Power BI](https://img.shields.io/badge/Power_BI-FFB000?style=for-the-badge&logo=power-bi&logoColor=white)](https://app.powerbi.com/view?r=eyJrIjoiZGQ1ZjFmNTMtZDJiYi00NmI5LWIwYzQtNzEzODcyMTlmZmU5IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/amrit4385)

This repository serves as documentation for the **AtliQ Hardwares Business Insights 360 - Power BI Project**, created as a self-learning project for the course: *Get Job Ready: Power BI Data Analytics for All Levels 2.0* by Codebasics.

The project was developed using **Microsoft Power BI Desktop 2.128.751.0** and published on **Microsoft Power BI Service**. Please note that project data files have not been uploaded to this repository in compliance with Codebasics' Data & Content Distribution Policy.

## Contents

Below are sectional links for the project:

- [BI 360 Live Report Link](#Business-Insights-360-Live-Report-Link)
- [Introduction to AtliQ Hardware](#introduction-to-atliq-hardware)
- [Project Objective](#project-objective)
- [Tools used & Methodologies implemented](#Tools-Used)
- [About the Dataset](#about-the-dataset)
- [Data Integrity](#data-integrity)
- [Data Model](#data-model)
- [Project Implementation](#project-implementation)
- [BI 360 Report Overview](#bi-360-report-overview)
- [Conclusion](#conclusion)

---

# [Business Insights 360 Live Report Link](https://app.powerbi.com/view?r=eyJrIjoiZGQ1ZjFmNTMtZDJiYi00NmI5LWIwYzQtNzEzODcyMTlmZmU5IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

---

## Introduction to AtliQ Hardware

**Domain**: Consumer Goods  
**Functions**: Finance, Sales, Marketing, Supply Chain, Executive  

**AtliQ Hardwares** specializes in computer hardware and peripherals like PCs, mice, and printers, serving clients worldwide. The company operates under a predominantly B2B business model, selling products to stores such as **Croma**, **Best Buy**, **Staples**, and **Flipkart**, which then retail these products to end users.  
They sell through three key channels:  
1. **Retailer**: Brick & Mortar (e.g., Croma, Best Buy) and E-commerce (e.g., Amazon, Flipkart).  
2. **Direct**: AtliQ-owned stores like **AtliQ E-store** and **AtliQ Exclusive**.  
3. **Distributor**: For countries with restricted trade, e.g., **Neptune**.

---

## Project Objective

**Challenge:** Unexpected losses after expanding operations in America due to reliance on outdated Excel methods for data analysis.  
**Solution:** Implement **Microsoft Power BI** for analytics to leverage data and support informed decision-making, enabling AtliQ Hardware to outperform competitors.  

Key highlights of the Power BI dashboard include:  
## BI 360 Report Overview

I. **Home View:**  
Acts as the central navigation hub, offering seamless access to all dashboard sections along with a support guide and an information manual.

![Home View](https://github.com/amrit4385/Business_Insight_360/blob/main/Images/Home%20View.png)

II. **Finance View:**  
Provides tools for improved financial planning and cost management, including a Profit & Loss statement, visualized trends in Net Sales, and detailed breakdowns by product categories and customer segments.
![Finance View](https://github.com/amrit4385/Business_Insight_360/blob/main/Images/Finance%20View.png)

III. **Sales View:**  
Centers around enhancing revenue growth and monitoring customer performance, presenting insights like Gross Margin percentage variations across various customers and products.
![Sales View](https://github.com/amrit4385/Business_Insight_360/blob/main/Images/Sales%20View.png) 

IV. **Marketing View:**  
Focuses on increasing brand awareness and evaluating the effectiveness of marketing strategies, offering insights into segment performance, regional Net Profit percentage trends, and campaign ROI.
![Marketing View](https://github.com/amrit4385/Business_Insight_360/blob/main/Images/Marketing%20View.png)

V. **Supply Chain View:**  
Supports better inventory management and demand forecasting through visuals that highlight forecast accuracy and assess stock risks associated with specific products or customers.
![Supply Chain View](https://github.com/amrit4385/Business_Insight_360/blob/main/Images/Supply%20Chain%20View.png)

VI. **Executive View:**  
Provides a comprehensive summary for senior management, featuring critical business KPIs, revenue distribution across divisions and channels, top-performing customers and products, and trends in AtliQ’s market share.
![Executive View](https://github.com/amrit4385/Business_Insight_360/blob/main/Images/Executive%20View.png)

---

## Tools Used

- **Microsoft Power BI**: Data ETL, Data Modelling, Data Visualization, Dashboarding  
- **GitHub**: Documentation  

---

## Skills & Methodologies Implemented

- Data Cleaning (Power Query)
- Data Manipulation (DAX Measures & Columns, Numeric & Field Parameters)
- Data Modelling
- Data Visualization (Conditional Formatting, Custom Tooltip)
- Dashboarding (Filters, Slicers, Bookmarks, Page Navigation)
- Report Publishing (PBI Service & Report Optimization)
- Documentation

---

## About the Dataset

The dataset contains **11 tables** sourced from **MySQL Server** and **Excel Files**.  
Key highlights:  
- **Comprehensiveness**: ~5.8 million records.  
- **Relevance**: Updated to FY 2022.  
- **Citation**: Official reference available.

**Data Sources:**  
From MySQL Server:  
- dim_customer, dim_market, dim_product, fact_forecast_monthly, fact_sales_monthly, freight_cost, manufacturing_cost, post_invoice_deductions  

From Excel Files:  
- market_share, operational_expense, ns_gm_target  

---

## Data Integrity

### ROCCC Evaluation

- **Reliability**: **Moderate**  
  The dataset originates from Codebasics and consists of nine files. Each file was utilized effectively during the analysis.

- **Originality**: **High**  
  Provided directly by Codebasics, the dataset is a first-party resource.

- **Comprehensiveness**: **High**  
  With 11 files and approximately 5.8 million records, the dataset includes diverse dimensions for customer and product attributes, as well as extensive sales transaction data.

- **Current**: **Moderate**  
  Reflecting data up to FY 2022, the dataset is nearly two years old. Thus, trends and insights should be considered general patterns rather than time-specific findings.

- **Citation**: **High**  
  Proper references and citations ensure the credibility of the dataset.  

---

## Data Model
![Data Model](https://github.com/amrit4385/Business_Insight_360/blob/main/Images/Data%20Model%20Final.PNG)
---

## Project Implementation

The project was executed in **9 phases**. Key tasks include:  
- **Phase 1**: Data Wrangling with MySQL and Power BI.  
- **Phase 2**: ETL operations with Power Query (e.g., creating custom Date Table).  
- **Phase 3**: Data Modelling & Calculated Columns (e.g., Gross Margin Calculations).  
- **Phase 4-9**: Development of Dashboard Views (Finance, Sales, Marketing, Supply Chain, Executive) with interactive visuals.  

---

## BI 360 Report Overview

1. **Home View**: Central navigation hub with support manual.  
2. **Finance View**: Features P&L Statement, Net Sales trends, and breakdowns.  
3. **Sales View**: Tracks customer performance and Gross Margin % variance.  
4. **Marketing View**: Evaluates ROI and segment performance.  
5. **Supply Chain View**: Displays forecast accuracy and inventory risks.  
6. **Executive View**: High-level overview with KPIs and Market Share trends.

---

## Conclusion

The AtliQ Hardwares Power BI dashboard offers a comprehensive analysis across Finance, Sales, Marketing, Supply Chain, and Executive functions. By integrating critical metrics (Net Sales, Gross Margin, etc.) with interactive visualizations, the project empowers leadership with actionable insights for strategic decisions.


---
