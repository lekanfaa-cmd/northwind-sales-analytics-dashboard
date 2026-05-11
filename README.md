# Northwind Traders – Business Intelligence & Sales Analytics Dashboard

## Project Overview

This project presents a comprehensive Business Intelligence analysis developed for **Northwind Traders**, a global gourmet food supplier. Using Tableau, an interactive analytics solution was designed to provide executive management with a clear understanding of sales performance, product intelligence, regional operations, shipping efficiency, customer behavior, and workforce productivity.

The project was developed as a multi-dashboard reporting solution aimed at transforming raw operational data into actionable business insights that support strategic decision-making.

---

# Business Objectives

The primary objective of this project was to answer critical business questions relating to:

- Sales and revenue performance trends
- Product and category contribution to revenue
- Regional market performance
- Shipping and operational efficiency
- Employee productivity and sales contribution
- Customer value and strategic business risks
- The impact of discounts on revenue performance

The dashboards were designed to support data-driven decision-making while improving the visibility of key operational and financial metrics.

---

# Dashboard Structure

The Tableau solution was structured into four interactive dashboards to improve usability, storytelling, and executive reporting clarity.

---

## Dashboard 1 – Sales & Revenue Overview

This dashboard provides a high-level overview of the company’s financial and operational performance.

### KPIs Included
- Total Revenue
- Total Orders
- Average Order Value
- Total Customers

### Visualizations
- Revenue Trend Over Time
- Seasonality Analysis
- Monthly Revenue Patterns

### Key Insights
The analysis revealed that revenue growth was not completely stable across all periods. Several months consistently outperformed others, indicating the presence of seasonal sales patterns. The findings also showed that increases in revenue were not always driven by order volume alone, but also by increases in average order value.

This suggests that the business relies significantly on high-value transactions to sustain revenue growth.

---

## Dashboard 2 – Product & Category Intelligence

This dashboard focuses on evaluating product performance, category contribution, and the effectiveness of pricing strategies.

### Visualizations
- Top Categories by Revenue
- Top Products by Revenue
- Impact of Discontinued Products
- Discounts vs Revenue Analysis

### Key Insights
The analysis showed that revenue generation was concentrated among a small number of product categories and products. Certain discontinued products were also found to continue contributing significantly to total revenue, suggesting possible missed opportunities from discontinuation decisions.

Additionally, the relationship between discounts and revenue indicated that higher discounts do not consistently lead to increased sales performance. This highlights potential risks to profitability caused by aggressive discounting strategies.

---

## Dashboard 3 – Regional, Operational & People Performance

This dashboard analyzes geographical performance, logistics efficiency, and employee sales productivity.

### Visualizations
- Revenue by Country
- Top Cities by Revenue
- Shipping Efficiency by Shipper
- Employee Performance by Revenue

### Key Insights
The analysis revealed that revenue generation was heavily concentrated in a few countries and cities, indicating uneven market penetration across regions.

Shipping efficiency analysis showed variations in freight costs and delivery times across different shippers, highlighting operational inefficiencies in logistics management.

Employee performance analysis further revealed disparities in sales contributions among employees, with a small number of employees contributing a significant portion of total revenue.

---

## Dashboard 4 – Advanced Strategic Insights

This dashboard focuses on deeper analytical insights relating to customer value, operational risks, and strategic opportunities.

### Visualizations
- Customer Lifetime Value
- Low Performance Months
- Shipping Cost by Region
- Discount Behaviour by Employee

### Key Insights
The analysis identified that a small group of customers generated a disproportionately large percentage of total revenue, creating customer concentration risk.

Low-performance months were also identified, indicating periods where the company is more vulnerable to reduced sales activity. Shipping cost analysis showed that some regions incur disproportionately high freight expenses, suggesting inefficiencies in routing or logistics management.

Discount behaviour analysis revealed inconsistencies in discount application across employees, which may negatively impact overall profitability.

---

# Tools & Technologies Used

| Tool | Purpose |
|------|---------|
| Tableau | Dashboard Development & Data Visualization |
| Excel | Data Cleaning & Preparation |
| SQL | Data Querying & Calculations |
| GitHub | Project Documentation & Portfolio Hosting |

---

# Business Value Delivered

This project demonstrates how Business Intelligence tools can be used to:

- Improve executive decision-making
- Monitor sales and operational performance
- Identify strategic business risks
- Optimize pricing and discount strategies
- Improve logistics and shipping efficiency
- Evaluate employee productivity
- Analyze customer value and purchasing behavior

---

# Repository Structure

```plaintext
northwind-sales-analytics-dashboard/

│── README.md
│
├── dashboards/
│     └── northwind_dashboard.twbx
│
├── reports/
│     └── northwind_bi_report.pdf
│
├── images/
│     ├── sales_dashboard.png
│     ├── product_dashboard.png
│     ├── operations_dashboard.png
│     └── advanced_dashboard.png
│
└── datasets/
      └── northwind_dataset.csv
