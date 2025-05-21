# Power BI Supply Chain Analytics Report

This repository contains an interactive Power BI report featuring three comprehensive dashboards designed to analyze and optimize supply chain performance. The report covers metrics around revenue, product performance, and supplier efficiency to support data-driven decision-making.

## 📊 Dashboards Overview

### 1. Overview Dashboard

This dashboard gives a consolidated summary of the business performance, combining financial, operational, and customer insights.

**Key Elements:**
- **KPIs:** Total Revenue, Total Products Sold, Total Costs, Average Profit Margin, Stock Level
- **Visuals:**
  - Doughnut chart: Total Revenue by Customer Demographics
  - Doughnut chart: Average Defect Rate (%) by Product Type
  - Clustered Bar Chart: Total Revenue by Product Type
  - Clustered Bar Chart: Total Revenue by SKU
  - Stacked Column Chart: Total Revenue by Shipping Carriers
  - Table: Supplier Name and Average Profit Margin

---

### 2. Product Insights Dashboard

This dashboard provides a detailed analysis of product-level performance and inventory dynamics.

**Key Elements:**
- **KPIs:** Total Revenue, Total Products Sold, Stock Level, Order Quantity
- **Visuals:**
  - Stacked Column Chart: Order Quantities by SKU
  - Stacked Column Chart: Stock Levels by SKU
  - Stacked Column Chart: Manufacturing Lead Time by Category & SKU
  - Doughnut Chart: Average Profit Margin by Product Type
  - Scatter Chart: Price vs. Total Products Sold by SKU and Product Type

---

### 3. Supplier Insights Dashboard

This dashboard focuses on supplier-level analysis and cost efficiency.

**Key Elements:**
- **Visuals:**
  - Doughnut Chart: Total Cost by Transportation Modes
  - Doughnut Chart: Average Defect Rate (%) by Transportation Modes
  - Stacked Bar Chart: Supplier Performance Analysis
  - Table: Supplier Name and Stock Level
  - Scatter Chart: Profit Margin and Defect Rates by Supplier Name

---

### 🔁 Common Features Across Dashboards

- **Page Navigator:** Enables seamless navigation across "Overview", "Products", and "Supplier" dashboards.
- **Slicers Available on All Pages:**
  - Filter by **SKU**
  - Filter by **Supplier Name**

---


## 📂 Dataset Used

The report is built using a sample supply chain dataset containing transactional and operational data related to revenue, stock, suppliers, product types, shipping, and defect rates.


- 📥 [Download Dataset (Google Drive)](https://drive.google.com/file/d/1QY-oR_8Yk8zmjFxIYv4iGdcnuiiBrSIL/view)

## 🛠 Tools Used

- **Power BI Desktop**
- **DAX** (Data Analysis Expressions)
- **CSV** (as data sources)


