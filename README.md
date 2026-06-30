Sales Performance Analytics using PySpark, SQL & Power BI
📌 Project Overview

This project demonstrates an end-to-end Sales Performance Analytics pipeline built using PySpark, Databricks, SQL, and Power BI. It focuses on ingesting raw sales data, performing large-scale data transformations, validating data quality, designing a dimensional data warehouse, and generating business insights through interactive dashboards.

The project follows modern data engineering practices including incremental data processing, data quality validation, and dimensional modeling to support business intelligence reporting.

🚀 Tech Stack
PySpark
Databricks
Databricks SQL
Delta Tables
SQL
Power BI
Git & GitHub
📂 Project Structure
Sales-Performance-Analytics/
│
├── 01_PySpark_ETL.ipynb
├── 02_Business_Analysis_SQL.ipynb
├── 03_Data_Quality_Checks.ipynb
└── README.md
📁 Notebook Description
📘 01_PySpark_ETL.ipynb

This notebook performs the complete ETL pipeline.

Key Tasks

Read raw sales dataset
Define custom schema using StructType
Clean and transform data
Handle null and invalid values
Perform incremental data loading
Create Delta tables
Generate Fact and Dimension tables
Prepare analytical dataset for reporting
📙 02_Business_Analysis_SQL.ipynb

This notebook contains SQL queries to answer business questions such as:

Total Sales
Monthly Revenue
Top Performing Products
Regional Sales Analysis
Customer Segment Analysis
Profit Analysis
Category-wise Performance
Sales Trend Analysis
📗 03_Data_Quality_Checks.ipynb

This notebook validates the quality of the processed data.

Data quality checks include:

Duplicate detection
Missing value validation
Blank value checks
Primary key validation
Fact table integrity checks
Dimension table consistency
Referential integrity verification
🔄 ETL Workflow
Raw Sales Data
        │
        ▼
PySpark Data Ingestion
        │
        ▼
Data Cleaning & Transformation
        │
        ▼
Data Quality Validation
        │
        ▼
Incremental Loading
        │
        ▼
Delta Tables
        │
        ▼
Fact & Dimension Tables
        │
        ▼
Business SQL Analysis
        │
        ▼
Power BI Dashboard
📊 Data Warehouse Design

The project implements a Star Schema consisting of:

Fact Table
Fact_Sales
Dimension Tables
Dim_Customer
Dim_Product
Dim_Date
Dim_Region
Dim_Segment
✅ Features
Large-scale data processing using PySpark
Custom schema definition
Incremental ETL pipeline
Delta Lake integration
Star schema implementation
Fact & Dimension modeling
Data quality validation
SQL-based business analysis
Interactive Power BI reporting
📈 Business Insights Generated
Sales by Region
Sales by Category
Monthly Revenue Trend
Top Customers
Top Products
Profit Analysis
Segment Performance
Order Analysis
💡 Key Concepts Demonstrated
ETL Pipeline
PySpark DataFrames
Data Transformation
Incremental Loading
Data Validation
Delta Tables
SQL Analytics
Dimensional Modeling
Star Schema
Business Intelligence
🎯 Skills Demonstrated
Data Engineering
Data Cleaning
SQL Analytics
Data Warehousing
PySpark
Databricks
Power BI
Data Quality Management
👨‍💻 Author

Surya Teja

B.Tech Mining Engineering | Data Analytics Enthusiast
