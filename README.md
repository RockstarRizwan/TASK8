# TASK8
POWERBI-TASK-8
# 📈 Interactive Sales Dashboard – Power BI

An interactive dashboard built using Power BI to visualize sales performance across time, regions, and product categories. This project helps convert raw sales data into actionable business insights.

---

## 🔍 Project Overview

This project uses a cleaned sales dataset (`Superstore_Sales.csv`) to create a business-ready Power BI dashboard. The dashboard highlights key performance metrics and trends using visuals such as:

- Monthly Sales Trend (Line Chart)
- Regional Sales Distribution (Bar Chart)
- Category-wise Sales Contribution (Donut Chart)
- Interactive Slicers for filtering by Region or Category

---

## 🧰 Tools & Technologies

- Power BI Desktop
- DAX (for date formatting and measures)
- Microsoft Excel / CSV (for sample data)
- GitHub (version control)

---

## 📁 Dataset Summary

| Column        | Description                       |
|---------------|-----------------------------------|
| Order Date    | Date of the order                 |
| Region        | Sales region                      |
| Category      | Product category (e.g., Tech)     |
| Sales         | Sales amount                      |
| Profit        | Profit generated from the sale    |

---

## 📌 Implementation Steps

1. Imported the dataset into Power BI.
2. Created a `Month-Year` column using DAX:
   ```DAX
   MonthYear = FORMAT('Sales'[Order Date], "MMM-YYYY")
