# Sales Performance Dashboard

## Project Overview

This project presents an interactive Sales Performance Dashboard developed using Power BI. The dashboard transforms raw business data into meaningful insights through visual analytics, enabling stakeholders to monitor sales performance, profitability, customer contributions, and regional trends.

The objective of this project is to provide a centralized and user-friendly platform for business performance analysis and data-driven decision-making.

---

## Tools Used

* Power BI Desktop
* DAX (Data Analysis Expressions)
* Data Visualization Techniques
* Interactive Dashboard Design

---

## Dataset

The project utilizes the Sample Superstore dataset, which contains information related to:

* Sales
* Profit
* Orders
* Customers
* Product Categories
* Regions
* Order Dates

---

## Dashboard Features

### Key Performance Indicators (KPIs)

* Total Sales
* Total Profit
* Total Orders
* Profit Margin %

### Visualizations

* Sales Trend Over Time
* Sales by Category
* Profit by Region
* Top 10 Customers by Sales

### Interactive Filters

* Region Slicer
* Category Slicer
* Order Date Slicer

---

## DAX Measure Used

```DAX
Profit Margin % =
DIVIDE(
    SUM('Sample - Superstore'[Profit]),
    SUM('Sample - Superstore'[Sales]),
    0
)
```

This measure calculates the percentage of profit generated from total sales.

---

## Business Insights

* Sales performance can be tracked over time using trend analysis.
* Product categories can be compared to identify top revenue generators.
* Regional profitability can be analyzed to support strategic planning.
* High-value customers can be identified for customer retention initiatives.
* Interactive filtering enables deeper exploration of business performance.

---

## Project Deliverables

* Power BI Dashboard (.pbix)
* Dashboard Screenshot
* Project Presentation (PPT)
* GitHub Repository Documentation

---

## Dashboard Preview

Add your dashboard screenshot here.

Example:

![Dashboard Screenshot](dashboard_screenshot.png)

---

## Conclusion

This dashboard demonstrates the practical application of Power BI for business intelligence and data visualization. By combining KPIs, trend analysis, customer insights, and interactive filters, the dashboard provides a comprehensive view of organizational performance and supports informed decision-making.

---

### Author

Himadri Singh
