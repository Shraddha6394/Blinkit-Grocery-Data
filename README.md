# 📊 Blinkit SQL Server Sales Analysis

## 🚀 Project Overview
This project analyzes **Blinkit grocery sales data** using **SQL Server**.  
The goal was to import raw CSV data, clean and standardize it, and run analytical queries to generate **KPIs** and uncover business insights.

---

## 📂 Dataset
- **Rows:** ~8,000  
- **Source:** BlinkIT Grocery Data (CSV)
- **Columns:**  
  - Item Fat Content  
  - Item Identifier  
  - Item Type  
  - Outlet Establishment Year  
  - Outlet Identifier  
  - Outlet Location Type  
  - Outlet Size  
  - Outlet Type  
  - Item Visibility  
  - Item Weight  
  - Total Sales  
  - Rating

---

## 🛠 Tools & Skills Used
- **SQL Server** — Data import, cleaning, transformations, aggregations
- **Data Cleaning** — Fixing inconsistent values, handling nulls, converting text to numeric
- **KPI Calculation** — Using `SUM`, `AVG`, `COUNT`, `GROUP BY`
- **Advanced SQL** — `CASE`, `PIVOT`, window functions (`OVER`, `RANK`, `%` share calculations)

---

## 🔍 Data Cleaning Steps
1. **Standardized values** — e.g., `LF` and `low fat` → `Low Fat`
2. **Removed duplicates**
3. **Handled missing values** in numeric columns
4. **Converted data types** for calculations:
   `
