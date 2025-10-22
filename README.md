
# 📊  Retail Sales Performance Analysis Dashboard
This repository contains an end-to-end Business Intelligence (BI) project focused on analyzing retail sales performance. The core deliverable is a dynamic, interactive Power BI dashboard that enables key stakeholders—from sales reps to executive management—to monitor crucial performance indicators and drive strategic decision-making.

# Project Scope and Objectives
The primary goal of this project is to transform complex raw sales data into a clear, actionable visualization layer.

Sales Monitoring: Provide real-time (or near real-time) tracking of key sales metrics.

Performance Deep-Dive: Analyze sales performance across different dimensions: products, customers, sales channels, and geographical regions.

Data-Driven Insights: Identify trends, seasonality, high-value customers, and underperforming product lines to optimize inventory and marketing strategies.

# Technical Components
1. Data Sources (CSV Files)
The analysis is built upon a well-structured dimensional model using the following data files:

Sales Analysis Dashboard.xlsx - Sales Orders.csv (Fact Table): The core transactional data, including:

OrderNumber, OrderDate, Ship Date

Order Quantity, Unit Price, Total Unit Cost, Total Revenue

References to the dimension tables (e.g., Customer Name Index, Product Description Index)

Sales Analysis Dashboard.xlsx - Customers.csv (Dimension Table): Master data for all customers, used for segmenting sales by client.

Sales Analysis Dashboard.xlsx - Products.csv (Dimension Table): Master data for product performance analysis.

Sales Analysis Dashboard.xlsx - Regions.csv (Dimension Table): Geographical data (Suburb, City, Postcode, Lat/Long) used for sophisticated geo-spatial analysis of sales distribution.

2. Data Modeling & Transformation
Technology: Power BI Desktop (sale dashboard analysis.pbix)

Schema: Implemented a Star Schema approach to efficiently handle large volumes of transactional data and facilitate fast querying.

Query Editor (Power Query): Steps for data cleaning, type conversion, and merging/appending queries are documented within the .pbix file.

3. Measures and KPI Calculation (DAX)
The Power BI model includes robust Data Analysis Expressions (DAX) to calculate essential business metrics:

Total Revenue

Total Unit Cost / Gross Margin

Order Count

Average Order Value (AOV)

Year-over-Year (YoY) Growth and Month-over-Month (MoM) comparisons.

4. Visualization (Power BI Dashboard)
The final dashboard (sale dashboard analysis.pbix) provides a multi-page, interactive view, allowing users to drill down into the data:

Executive Summary: High-level KPIs, Revenue vs. Cost trends, and overall growth metrics.

Product Performance: Ranked tables and charts to identify top-selling and low-performing products.

Customer Analysis: Segmentation by customer name and channel (Wholesale/Distributor) to highlight high-value clients.

Geographical View: Map visuals utilizing the Regions.csv data to show sales concentration and performance by city and region.
<img width="1344" height="750" alt="Sales Analysis" src="https://github.com/user-attachments/assets/38470a18-8271-43fd-80b2-3e8349d6ba76" />
<img width="1332" height="740" alt="Sales Analysis 2" src="https://github.com/user-attachments/assets/4ed5750e-e594-44dd-aa65-22fdc50ebc08" />

