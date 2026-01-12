# 💊 Pharmaceutical Sales & Inventory Analytics – Power BI

<p align="center">
  <img src="cover page/pharma_sales_background.jpg" alt="Pharmaceutical Sales & Inventory Analytics">
</p>  


## Project Overview
This project is an end-to-end Business Intelligence solution built using Microsoft Power BI to analyze pharmaceutical sales, inventory levels, and expiry risk. It covers the complete BI lifecycle — from raw data ingestion to a fully interactive, decision-ready dashboard.

The goal was to simulate how a pharmaceutical company would monitor revenue, stock, and product performance using a centralized analytics platform.

---

## Business Problem
Pharma businesses often operate with disconnected data across:
- Sales
- Products
- Inventory
- Suppliers

This results in:
- Manual Excel reporting taking 5–8 hours per cycle
- No real-time view of stock availability and expiry risk
- Limited visibility into product and regional performance

---

## Project Workflow

### 1️⃣ Data Collection
Multiple datasets were used to represent real pharma operations:
- Sales transactions
- Product and manufacturer master data
- Inventory and stock levels
- Supplier information

These datasets were imported into Power BI from Excel sources.

---

### 2️⃣ Data Cleaning & Transformation
Using Power Query:
- Removed duplicates and blank records
- Standardized column names and formats
- Converted data types for dates, numbers, and currencies
- Created calculated columns for inventory and expiry analysis
- Built a dedicated Date table for time intelligence

This ensured clean and analysis-ready data.

---

### 3️⃣ Data Modeling
A star-schema model was created with:
- Sales as the fact table
- Product, Date, Inventory, and Supplier as dimension tables

One-to-many relationships were defined to allow accurate filtering and aggregation across all visuals.

---

### 4️⃣ DAX Measures & Business Logic
Key business metrics were created using DAX:
- Total Sales
- Net Sales
- Gross Profit
- Profit Margin %
- Year-over-Year Growth
- Revenue Planning (Stock Available × Unit Price)
- Expiry Risk (12 / 18 / 24 months)

These measures made the dashboard fully dynamic and interactive.

---

### 5️⃣ Dashboard Design
The report was designed with a clean, executive-friendly layout:
- KPI cards for sales, growth, and profitability
- Bar charts for product and region performance
- Line charts for monthly and yearly trends
- Inventory and expiry risk visuals
- Slicers for date, product, region, and supplier

All visuals are fully interconnected for drill-down and self-service analysis.

---

### 6️⃣ Business Insights
The dashboard enables users to:
- Identify top-selling products and high-performing regions
- Detect slow-moving and near-expiry stock
- Monitor sales growth and profitability
- Compare supplier and sales agent performance
- Make faster and more informed commercial decisions

---

## Key Business Outcomes
- ~90% reduction in reporting time (from 5–8 hours to 10–15 minutes)
- ~15% improvement in stock availability through real-time monitoring
- $418K in revenue opportunity identified by tracking near-expiry inventory

---

## Tools & Technologies
- Power BI
- DAX
- Power Query
- Data Modeling (Star Schema)
- Time Intelligence
- Excel Data Sources

---

## Project Outcome
This project demonstrates how pharmaceutical sales and inventory data can be transformed into actionable business insights using modern BI practices. The dashboard provides a scalable foundation for revenue tracking, inventory optimization, and performance management.
