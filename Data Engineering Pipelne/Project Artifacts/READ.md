**Supply Chain Analytics Pipeline**

**Project Overview**

**Built a full end-to-end data engineering and analytics pipeline on supply chain data, transforming raw files into a relational database, and delivering business-ready dashboards for supply chain and market intelligence.**

**Tech Stack**
- Data Cleaning & Prep: Power Query, Excel
- Database: PostgreSQL 17 (via pgAdmin)
- Schema Design & ERD: Custom relational modeling
- Data Transformation: SQL (joins, constraints, indexes)
- Visualization: Tableau, Power BI

Dataset: DataCo Supply Chain (Kaggle)- https://www.kaggle.com/code/devraai/logistics-data-analysis-and-delay-prediction

**Pipeline Steps**

**1. Raw Data Ingestion**
- Imported 180K+ rows, 22 tables, 48 columns of raw logistics data.
- Cleaned for duplicates, nulls, and outliers.

**2. Data Cleaning**
- Standardized data types and formatting in Power Query.
- Performed enrichment and transformations in Excel.

**3. Database Design**
- Designed normalized schemas (Supply Chain, Order Mart, World Market).
- Built ERDs mapping relationships across:
- Customers | Orders | Sales | Products | Suppliers | Shippers | Employees

**4. Data Loading**
- Loaded datasets into PostgreSQL.
- Applied constraints, indexes, joins for performance + integrity.

**5. Data Modeling & Querying**
- Wrote SQL joins/views for:
- Delivery status tracking
- Order profitability
- Late shipment risk
- Regional sales trends

**6. Visualization & Insights**
- Connected PostgreSQL to Tableau & Power BI.

**Designed dashboards for:**
- Sales by Market & Region Profitability by Order
- Time-of-Day sales insights

**Key Skills Demonstrated**
- End-to-end ETL pipeline development
- Relational schema & ERD design
- SQL (joins, constraints, query optimization)
- Data visualization (Tableau & Power BI)
- Turning raw data into actionable supply chain insights
