
# Data Warehouse and Analytics Solution

This repository contains the implementation of a modern data warehouse and analytics solution built on SQL Server. The project focuses on consolidating data from multiple sources into a structured model to support analytical reporting and business decision-making.

---
## Architecture Overview

The solution follows a Medallion Architecture with three logical layers:

-  **Bronze Layer**: Ingests raw data from source systems (ERP and CRM) in CSV format, preserving original structure for traceability.
-  **Silver Layer**: Applies data cleansing, standardization, and normalization to ensure consistency and reliability.
-  **Gold Layer**: Provides curated, business-ready datasets modeled using a star schema, optimized for analytical queries and reporting.

---
## Solution Scope

This project includes:

-  Design and implementation of a layered data warehouse architecture.
-  Development of ETL pipelines for data ingestion and transformation
-  Construction of fact and dimension tables for analytics
-  Delivery of SQL-based analytical outputs to support business insights

---

## Business Objectives

The primary goal is to enable analytical reporting on sales data by consolidating information from multiple systems into a unified data model.

The solution supports analysis of:

-  Customer behavior
-  Product performance
-  Sales trends

## Data Engineering Specifications

-  **Data Sources:** ERP and CRM datasets provided as CSV files
-  **Data Processing:** Data quality issues are identified and resolved during transformation
-  **Integration:** Data is unified into a single analytical model
-  **Scope:** Focus on current-state data (no historization)
-  **Documentation:** Data models and processes are documented for technical and business use

## 📂 Repository Structure
```
data-warehouse-project/
│
├── datasets/        # Source data (ERP and CRM)
├── docs/            # Architecture, data models, and documentation
├── scripts/         # SQL scripts for ingestion and transformation (bronze/silver/gold)
├── tests/           # Data validation and quality checks
├── README.md
├── LICENSE
├── .gitignore
└── requirements.txt
```
---

