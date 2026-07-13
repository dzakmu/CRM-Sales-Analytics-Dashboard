# CRM Sales Analytics Dashboard

An interactive **Power BI CRM Sales Analytics Dashboard** developed to analyze sales performance, product performance, sales pipeline, and team effectiveness using Business Intelligence techniques.

---

## Project Overview

This project transforms raw CRM sales opportunity data into an interactive business intelligence dashboard that enables stakeholders to monitor sales performance, evaluate product contribution, analyze pipeline efficiency, and identify top-performing sales teams.

The dashboard was built using **Power BI**, **Power Query**, and **DAX**, following a star schema data model to ensure scalable and efficient analysis.

---

## Business Questions

The dashboard is designed to answer the following business questions:

- How much revenue has been generated?
- How many deals have been won and lost?
- Which products generate the highest revenue?
- Which sales agents and managers perform the best?
- Which sectors and regions contribute the most revenue?
- How does revenue change over time?
- How does revenue change from quarter to quarter?
- Which products achieve better win rates?
- How is the sales pipeline distributed across deal stages?

---

# Dataset

The project uses a CRM Sales Opportunities dataset consisting of four related tables.

| Table | Description |
|--------|-------------|
| Accounts | Company information |
| Products | Product catalog |
| Sales Pipeline | Sales opportunities and transactions |
| Sales Teams | Sales agent and manager information |

---

# Data Preparation

The following preprocessing steps were performed before building the dashboard:

- Imported multiple CSV datasets
- Cleaned missing values
- Corrected inconsistent product names
- Standardized data types
- Created a Calendar table
- Built a Star Schema data model
- Established relationships between fact and dimension tables
- Developed DAX measures for KPIs and business metrics

---

# Data Model

The dashboard follows a **Star Schema** design.

**Fact Table**
- Sales Pipeline

**Dimension Tables**
- Accounts
- Products
- Sales Teams
- Calendar

---

# Dashboard Pages

## 1. Executive Sales Dashboard

Provides an executive-level overview of business performance.

### a. KPIs

- Total Revenue
- Total Deals
- Won Deals
- Lost Deals
- Win Rate
- Average Deal Value

### b. Visualizations

- Revenue Trend by Month
- Revenue by Sales Agent
- Revenue by Product
- Revenue by Sector
- Sales Pipeline Funnel
- Top Product
- Top Region
- Top Sector
- Top Sales Agent

### c. Key Insights

- Total Revenue reached **$10M**.
- More than **9K sales opportunities** were recorded.
- Overall **Win Rate is 63.15%**.
- **GTX Pro** generated the highest revenue.
- **West Region** contributed the highest total revenue.
- **Darcel Schlecht** achieved the highest sales revenue.

---

## 2️. Product Performance Dashboard

Focuses on product-level analysis.

### a. Visualizations

- Product Revenue by Region
- Win Rate by Product
- Revenue by Product
- Product Revenue Trend
- Top Sales Agent per Product

### b. Key Insights

- GTX Pro is the highest-performing product.
- Product performance differs across regional offices.
- Premium products generate significantly higher revenue.
- Win rates vary across products, indicating differences in sales effectiveness.

---

## 3️. Sales Performance Dashboard

Analyzes individual sales performance and team effectiveness.

### Visualizations

- Revenue by Sales Agent
- Win Rate by Sales Agent
- Won Deals by Sales Agent
- Revenue by Manager
- Revenue by Quarter
- Sales Performance Table

### Key Insights

- Revenue is concentrated among several top-performing sales agents.
- Sales agents exhibit different win rates, indicating varying sales effectiveness.
- Revenue performance differs across managers and their teams.
- Quarterly revenue trends help identify seasonal patterns and business performance changes throughout the year.

---

# KPIs

The dashboard includes the following DAX measures:

- Total Revenue
- Total Deals
- Won Deals
- Lost Deals
- Win Rate
- Average Deal Value

---

## Features

- Interactive slicers
- Navigation buttons
- Dynamic KPI cards
- Quarterly Revenue Analysis
- Product Performance Analysis
- Sales Performance Analysis
- Deal Stage Funnel
- Regional Performance Analysis
- Win Rate Analysis
- Custom Tooltip
  
---

# Business Insights

### Executive Summary

- Total revenue exceeded **$10 million**.
- Overall win rate reached **63.15%**, indicating strong sales conversion.
- GTX Pro is the company's primary revenue driver.
- Retail contributes the highest revenue among all sectors.
- West Region consistently outperforms other regions.

### Product Insights

- Premium GTX products dominate total revenue.
- Product demand varies significantly across regions.
- Win rates differ across product categories.

### Sales Insights

- Revenue is concentrated among top-performing sales agents.
- Win rates vary across sales agents, highlighting differences in conversion efficiency.
- Revenue trends fluctuate across quarters, providing insight into seasonal sales performance.
- Manager performance differs across teams, suggesting opportunities for coaching and resource allocation.

---

# Business Recommendations

- Continue investing in GTX Pro due to its strong revenue contribution.
- Analyze lost opportunities to improve conversion rates.
- Replicate strategies from top-performing sales agents.
- Increase marketing efforts for lower-performing products.
- Expand successful sales practices from the West Region to other regions.

---

# Tools & Technologies

- Power BI Desktop
- Power Query
- DAX
- Data Modeling
- Microsoft Excel / CSV
- GitHub

---

# Skills Demonstrated

- Data Cleaning
- Data Transformation
- Data Modeling
- Star Schema Design
- DAX Development
- KPI Design
- Dashboard Design
- Business Intelligence
- Data Visualization
- Interactive Reporting

---

# Dashboard Preview

## Executive Sales Dashboard

<img width="1287" height="725" alt="image" src="https://github.com/user-attachments/assets/005c189e-52c3-4d0a-b56f-0a35901c08a8" />

## Product Performance Dashboard

<img width="1291" height="736" alt="image" src="https://github.com/user-attachments/assets/5a19f5bc-b4fc-413c-94c6-35fea7d7d455" />

## Sales Performance Dashboard

<img width="1292" height="730" alt="image" src="https://github.com/user-attachments/assets/8c99013c-5b5a-48c8-af30-d6f8926d836a" />

---

# Repository Structure

```
CRM-Sales-Analytics-Dashboard
│
├── Dashboard
│   └── CRM Sales Analytics.pbix
│
├── Dataset
│   ├── accounts.csv
│   ├── products.csv
│   ├── sales_pipeline.csv
│   └── sales_teams.csv
│
├── Images
│   ├── executive_dashboard.png
│   ├── product_performance.png
│   ├── sales_performance.png
│   └── data_model.png
│
└── README.md
```

---

# Future Improvements

- Forecasting sales revenue
- Customer segmentation
- Drill-through reports
- Row-Level Security (RLS)
- Power BI Service deployment

---

# Author

**Muhammad Dzaky Mu'ammar**
