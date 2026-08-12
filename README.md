# Drug-Sales-Power-BI-Dashboard
Interactive Drug Sales Dashboard built with Power BI, featuring sales performance analysis, KPIs, product insights, and business intelligence reporting.

## 💊 Drug Sales Power BI Dashboard
## 📌 Project Overview
This project analyzes drug sales data using Power BI to track revenue, profit, and customer behavior across products and time periods. The dashboard turns raw transactional data into an interactive tool that helps stakeholders identify top-performing drugs, understand customer segments, and monitor sales trends over time.

## 🎯 Business Objective
The goal is to give sales and business teams a single, interactive view of performance — helping them answer questions like: Which drugs generate the most revenue and profit? Who are the most valuable customers? How does demand shift across months and quarters? The dashboard supports faster, data-driven decisions on inventory, pricing, and customer targeting.

## 🛠️ Tools & Technologies
- **Power BI Desktop** — data modeling, DAX measures, and report design
- **DAX** — calculated columns and measures for KPIs (Revenue, Profit, Profit Margin)
- **Power Query** — data cleaning and transformation
- **Star Schema** — data modeling approach for scalable analysis

## 📊 Key KPIs
- Total Revenue
- Total Profit & Profit Margin
- Total Quantity Sold
- Cost of Goods Sold (COGS)
- Top / Bottom performing products
- Customer segmentation metrics

## 📈 Dashboard Features
- **Top/Bottom Analysis** — ranks products by revenue and profit to highlight best and worst performers
- **Customers Analysis** — breaks down sales by customer segment and behavior
- **Trend Analysis** — tracks sales performance over time (by year, quarter, and month)
- Interactive filters (Drug Name, Year, Quarter, Month) for dynamic drill-down

## 🔍 Key Insights
- A small group of top products drive the majority of total revenue and profit
- Sales show clear seasonal patterns across quarters
- Customer segments differ significantly in average order value and purchase frequency

## 🖼️ Dashboard Preview

<img width="1920" height="1080" alt="Trend Analysis" src="https://github.com/user-attachments/assets/17e1f12c-9828-4925-b612-367d73ad85b2" />
<img width="1920" height="1080" alt="Top - Bottom Analysis" src="https://github.com/user-attachments/assets/b5b15b3e-a6ba-464f-8a7f-3d03c823e836" />
<img width="1920" height="1080" alt="Customers Analysis" src="https://github.com/user-attachments/assets/2535972e-3e62-4021-aba8-e24dc48059a2" />

## 📁 Project Files
- `Drug Dashboard.pbix` — the Power BI report file
- `FactTable.csv` — sales transactions data
- `DrugLookup.csv` — product/drug reference data
- `CustomerTable.csv` — customer reference data

## 👤 Author
**Amr Ahmed**
[LinkedIn](#) | [Upwork](#)

## 🧩 Data Model
The project follows a **Star Schema** approach to organize the data and support efficient analysis in Power BI.

### Fact Table
**FactTable**
- Sales transactions
- Quantity
- Cost of Goods Sold (COGS)
- Revenue
- Profit
- Profit Margin
- Date-related sales metrics

### Dimension Tables
**DrugLookup**
- Drug information
- Product attributes
- Drug categories

**CustomerTable**
- Customer information
- Customer attributes
- Customer segmentation

### Model Design
The fact table is connected to the relevant dimension tables through unique keys, creating a structured analytical model that supports:
- Product-level analysis
- Customer-level analysis
- Time-based analysis
- Revenue and profit analysis
- Top / Bottom product analysis
- 
- Interactive filtering and drill-down

This modeling approach improves data organization, reduces redundancy, and provides a scalable foundation for DAX calculations and Power BI reporting.
