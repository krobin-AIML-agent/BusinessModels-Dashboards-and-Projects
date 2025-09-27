Supply Chain Analytics Pipeline
🔎 Project Overview

This project demonstrates an end-to-end data engineering and analytics workflow built on real-world style supply chain data. Starting with a raw dataset, I designed a relational schema, performed data cleaning and transformation, and created visual analytics dashboards to deliver actionable insights for supply chain and market analysis.

🛠️ Tech Stack

Data Cleaning & Prep: Power Query, Excel

Database: PostgreSQL 17

Schema Design & ERD: pgAdmin, custom relational modeling

Data Transformation: SQL (joins, constraints, indexes)

Visualization: Tableau & Power BI

Data Source: DataCo Supply Chain Dataset (https://www.kaggle.com/code/devraai/logistics-data-analysis-and-delay-prediction)

📂 Pipeline Steps

Raw Data Ingestion

Imported supply chain dataset (180K+ rows, 22 tables, 48 columns).

Cleaned data for consistency (duplicates, nulls, outliers).

Data Cleaning

Standardized fields in Power Query (data types, formatting).

Additional transformations and enrichment in Excel.

Database Design

Designed normalized schema (Supply Chain, Order Mart, World Market, etc.).

Built Entity Relationship Diagrams (ERDs) to map relationships between:

Customers

Orders

Sales

Products

Suppliers

Shippers

Employees

Data Loading

Uploaded cleaned datasets into PostgreSQL.

Implemented constraints, indexes, and joins for performance and integrity.

Data Modeling & Querying

Wrote SQL joins to connect business entities.

Created views for delivery status, order profitability, late shipment risk, and regional sales trends.

Visualization & Insights

Connected PostgreSQL to Tableau and Power BI.

Designed dashboards highlighting:

📦 Sales by Market & Region by Order Profitability

📈 Sample Visuals

ERD Models: Logical schema showing data relationships.

Tableau Dashboard: Sales by Market & Region with time-of-day insights.

Power BI Dashboard: Interactive supply chain KPIs.

🎯 Key Skills Demonstrated

End-to-end ETL pipeline development

Database schema design & ER modeling

SQL for analysis (joins, constraints, query optimization)

Data visualization in Tableau & Power BI

Translating raw data into business-ready insights
