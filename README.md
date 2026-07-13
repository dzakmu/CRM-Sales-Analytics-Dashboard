# 📊 CRM Sales Analytics Dashboard

An interactive **Power BI CRM Sales Analytics Dashboard** developed to analyze sales performance, product performance, sales pipeline, and team effectiveness using Business Intelligence techniques.

---

## 📌 Project Overview

This project transforms raw CRM sales opportunity data into an interactive business intelligence dashboard that enables stakeholders to monitor sales performance, evaluate product contribution, analyze pipeline efficiency, and identify top-performing sales teams.

The dashboard was built using **Power BI**, **Power Query**, and **DAX**, following a star schema data model to ensure scalable and efficient analysis.

---

# 🎯 Business Objectives

The dashboard aims to answer the following business questions:

- How much revenue has been generated?
- How many sales opportunities were successfully converted?
- Which products generate the highest revenue?
- Which sales agents and managers perform the best?
- Which sectors and regions contribute the most revenue?
- How does revenue change over time?
- Which products achieve better win rates?
- How does the sales pipeline progress across different deal stages?

---

# 📂 Dataset

The project uses a CRM Sales Opportunities dataset consisting of four related tables.

| Table | Description |
|--------|-------------|
| Accounts | Company information |
| Products | Product catalog |
| Sales Pipeline | Sales opportunities and transactions |
| Sales Teams | Sales agent and manager information |

---

# 🛠️ Data Preparation

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

# 🏗️ Data Model

The dashboard follows a **Star Schema** design.

**Fact Table**
- Sales Pipeline

**Dimension Tables**
- Accounts
- Products
- Sales Teams
- Calendar

---

# 📈 Dashboard Pages

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

Evaluates individual and team performance.

### a. Visualizations

- Revenue by Sales Agent
- Win Rate by Sales Agent
- Won Deals by Sales Agent
- Revenue by Manager
- Revenue Trend by Quarter
- Sales Performance Table

### b. Key Insights

- Revenue distribution is concentrated among several top-performing sales agents.
- Some agents maintain higher win rates despite handling fewer opportunities.
- Manager performance varies across teams.
- Revenue trends show seasonal fluctuations throughout the year.

---

# 📊 KPIs

The dashboard includes the following DAX measures:

- Total Revenue
- Total Deals
- Won Deals
- Lost Deals
- Win Rate
- Average Deal Value

---

# 🚀 Features

- Interactive slicers
- Navigation buttons
- Dynamic KPI cards
- Calendar table
- Star schema data model
- Sales funnel visualization
- Product performance analysis
- Sales performance analysis
- Regional analysis
- Custom tooltip page

---

# 💡 Business Insights

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
- High revenue does not always indicate the highest win rate.
- Manager performance differs considerably across sales teams.

---

# 📌 Business Recommendations

- Continue investing in GTX Pro due to its strong revenue contribution.
- Analyze lost opportunities to improve conversion rates.
- Replicate strategies from top-performing sales agents.
- Increase marketing efforts for lower-performing products.
- Expand successful sales practices from the West Region to other regions.

---

# 🧰 Tools & Technologies

- Power BI Desktop
- Power Query
- DAX
- Data Modeling
- Microsoft Excel / CSV
- GitHub

---

# 📚 Skills Demonstrated

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

# 📷 Dashboard Preview

## Executive Sales Dashboard

*(Insert Screenshot)*

## Product Performance Dashboard

*(Insert Screenshot)*

## Sales Performance Dashboard

*(Insert Screenshot)*

---

# 📁 Repository Structure

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

# 🔮 Future Improvements

- Quarter-over-Quarter analysis
- Forecasting sales revenue
- Customer segmentation
- Drill-through reports
- Row-Level Security (RLS)
- Power BI Service deployment

---

# 👨‍💻 Author

**Muhammad Dzaky Mu'ammar**
