# Data-Warehouse-Implementation-Project
Implemented dimensional data models in Oracle Cloud, created ETL data pipelines in Talend, and designed data visualizations for sales analysis in Tableau
# Project Overview
Guac2Guac, a fresh produce retailer, needed a data warehouse to centralize sales, customer, and store data. The company previously relied on manual, spreadsheet-based reports, which were prone to errors and difficult to manage. To address this, I built a dimensional model using a star schema to improve data access and reporting.

# Methodology
I followed Kimball’s approach, structuring data around key business processes. The star schema included dimensions such as Product, Customer, Store, Employee, Date, Promotion, and Payment, with the Sales fact table capturing transaction details like quantity sold and revenue.

# Key Activities
Dimensional Modeling: Created a star schema to organize and centralize sales data for analysis.
ETL Pipeline: Developed an ETL process using Talend Open Studio to load data from flat files into Oracle Cloud Autonomous Data Warehouse, handling slowly changing dimensions.
BI Integration: Connected the warehouse to Tableau for data visualization and business insights.
Outcomes
The project improved data management and analysis for Guac2Guac. Using Tableau, the VP of Sales can now easily analyze sales trends, customer behavior, and the impact of promotions, leading to better-informed business decisions.

# Tools Used
Data Warehousing: Oracle Cloud Autonomous Data Warehouse
ETL: Talend Open Studio
Business Intelligence: Tableau
