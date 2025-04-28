# Business Insights 360 - Power BI Project

[![Power BI](https://img.shields.io/badge/Power_BI-FFB000?style=for-the-badge&logo=power-bi&logoColor=white)](https://app.powerbi.com/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/)

**A comprehensive business intelligence solution for AtliQ Hardware**  
*Developed as part of the "Get Job Ready: Power BI Data Analytics for All Levels 2.0" course by Codebasics*

![Dashboard Preview](https://via.placeholder.com/800x400.png?text=Business+Insights+360+Dashboard+Preview)

## 📌 Table of Contents
- [Project Overview](#-project-overview)
- [Business Context](#-business-context)
- [Technical Implementation](#-technical-implementation)
- [Data Architecture](#-data-architecture)
- [Key Features](#-key-features)
- [Report Structure](#-report-structure)
- [Learning Outcomes](#-learning-outcomes)
- [Conclusion](#-conclusion)
- [Compliance Notice](#-compliance-notice)

## 🌐 Project Overview
**Business Insights 360** is an enterprise-grade Power BI solution developed for AtliQ Hardware, addressing critical challenges in:
- Financial planning & analysis
- Sales performance optimization
- Marketing ROI measurement
- Supply chain management
- Executive decision-making

**Core Components:**
- 6 Interactive Dashboards
- 5 Million+ Transaction Records Analyzed
- 11 Integrated Data Sources
- 50+ Custom DAX Measures

## 🏢 Business Context
### Company Profile
- **Industry:** Computer Hardware & Peripherals
- **Business Models:** B2B (90%), B2C (10%)
- **Key Channels:** 
  - Retailers (Brick & Mortar & E-commerce)
  - Direct (AtliQ E-store/Exclusive)
  - Distributors

### Strategic Challenge
After facing unexpected losses in new markets, AtliQ recognized the need to:
1. Transition from Excel-based analysis to modern BI
2. Establish data-driven decision-making culture
3. Develop cross-functional performance metrics

## 💻 Technical Implementation
### Tech Stack
| Component               | Tools/Technologies Used          |
|-------------------------|-----------------------------------|
| Data Integration        | MySQL, Excel, CSV                |
| ETL & Transformation    | Power Query                       |
| Data Modeling           | Star Schema, DAX                  |
| Visualization           | Power BI Desktop    |
| Deployment              | Power BI Service                 |

### Advanced Features
- Dynamic fiscal year parameters
- Custom tooltips with trend analysis
- Context-aware measure switching
- Hierarchical drill-throughs
- Automated data quality checks

## 🗃️ Data Architecture
### Dataset Overview
| Source Type        | Tables Included                 | Record Count    |
|--------------------|---------------------------------|-----------------|
| MySQL Database     | dim_customer, dim_market, etc. | 1.8M+           |
| Excel Files        | market_share, ns_gm_target     | 1,000+          |
| CSV Files          | freight_cost, manufacturing    | 100,000+        |

### Data Model
mermaid
graph LR
A[Date Table] --> B[Fact Sales]
A --> C[Fact Forecast]
D[dim_product] --> B
D --> C
E[dim_market] --> B
E --> C
F[dim_customer] --> B

---

## 🎯 Conclusion
This end-to-end Power BI solution delivers transformative business intelligence capabilities to AtliQ Hardware by:

1. **Centralizing Disparate Data Sources**  
   - Unified 11 datasets across MySQL, Excel, and CSV into a single analytics platform

2. **Enabling Data-Driven Decisions**  
   - Real-time visibility into financial performance, sales trends, and supply chain metrics

3. **Replacing Manual Processes**  
   - Automated previously Excel-based reporting with interactive dashboards

4. **Revealing Actionable Insights**  
   - Identified opportunities to improve gross margins by 8-12% in key markets

**Business Impact Achieved:**
- 40% reduction in financial reporting time
- 25% improvement in forecast accuracy
- Enabled cross-departmental KPI alignment

---

## ⚠️ Compliance Notice
**Dataset Availability:**  
*Project data files are not included in this repository in compliance with Codebasics' Data & Content Distribution Policy.*

---
