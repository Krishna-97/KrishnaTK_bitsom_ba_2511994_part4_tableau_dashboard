# Part 4 – Tableau Executive Dashboard & Data Storytelling

## Project Overview

This project presents an interactive Tableau Executive Dashboard developed for retail business leadership. The dashboard consolidates sales, profitability, customer behavior, shipping performance, product returns, and discount analysis into a single interface to support executive decision-making.

---

# Business Problem

Retail executives require a centralized dashboard to monitor key business performance indicators, identify profitable growth opportunities, understand customer behavior, optimize shipping operations, and reduce business risks.

The objective of this project is to transform transactional sales data into actionable business intelligence using Tableau.

---

# Dataset Description

The dataset contains retail sales transaction records including:

* Order ID
* Order Date
* Ship Date
* Customer Segment
* Region
* State
* Category
* Sub-Category
* Sales
* Profit
* Quantity
* Discount
* Shipping Mode
* Returned Orders
* Customer Information

The dataset is stored in:

```text
data/dashboard_sales_data.xlsx
```

---

# Tableau Workbook

Workbook Name

```text
tableau/executive_dashboard.twbx
```

The workbook contains individual worksheets along with a fully interactive executive dashboard.

---

# Calculated Fields Created

The dashboard includes the following calculated fields:

1. Profit Margin
2. Cost
3. Average Order Value
4. Return Rate
5. Shipping Delay
6. Shipping Delay Bucket

These calculations provide additional business metrics beyond the raw dataset.

---

# Dashboard Components

The executive dashboard includes:

* Total Sales KPI
* Total Profit KPI
* Profit Margin KPI
* Return Rate KPI
* Monthly Sales Trend
* Regional Performance
* Category Profitability
* Customer Segment Analysis
* Discount vs Profit Analysis
* Shipping Performance
* Return Analysis

---

# Interactive Filters

The dashboard supports dynamic filtering using:

* Region
* Category
* Customer Segment
* Ship Mode
* Order Date
* Campaign Channel (if available)

A dashboard filter action enables users to click on one visualization and update the remaining charts automatically.

---

# Key Business Insights

Major findings include:

* Technology is the most profitable category.
* Higher discounts reduce profitability.
* Corporate customers generate higher average order values.
* Regional sales performance varies significantly.
* Shipping delays affect operational efficiency.
* Product returns remain concentrated within selected categories.
* Seasonal sales patterns influence revenue.
* Profitability depends on both pricing strategy and operational efficiency.

---

# Dashboard Story Summary

The dashboard demonstrates how sales performance, profitability, operational efficiency, customer behavior, and product returns interact to influence overall business success. It provides executives with a single source of truth for monitoring performance and making data-driven decisions.

---

# Assumptions

* Return Rate is calculated using returned orders divided by total orders.
* Average Order Value is based on distinct Order IDs.
* Shipping Delay is calculated as the difference between Ship Date and Order Date.
* Profit Margin is calculated as Profit divided by Sales.
* Missing values were assumed to be cleaned before dashboard development.

---

# Limitations

* Historical data only; no predictive forecasting.
* External economic and competitive factors are excluded.
* Customer satisfaction metrics are unavailable.
* Inventory and operational cost data are not included.

---

# Repository Structure

```text
part4_tableau_dashboard/
│
├── data/
├── tableau/
├── outputs/
├── screenshots/
└── README.md
```

---

# Screenshots Included

* full_dashboard.png
* sales_trend_view.png
* regional_performance_view.png
* category_profitability_view.png
* filter_interaction_view.png

---

# Software Used

* Tableau Desktop
* Microsoft Excel
* GitHub

---

# Conclusion

This Tableau Executive Dashboard transforms transactional retail data into an executive reporting solution by combining key performance indicators, interactive visualizations, calculated metrics, and business storytelling. The dashboard enables leadership teams to monitor organizational performance, identify risks, and make informed strategic decisions.
