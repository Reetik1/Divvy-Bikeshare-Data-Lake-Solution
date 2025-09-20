# Divvy Bikeshare Data Lake Solution

A complete data engineering solution built on Azure Databricks, transforming raw Chicago bikeshare data into business-ready analytics using modern lakehouse architecture.

## What I Built

I designed and implemented an end-to-end data pipeline that processes over 4.5 million trip records and 1.9 million payment transactions, creating a star schema data warehouse optimized for business intelligence and analytics.

## Architecture
 **This project follows the complete medallion architecture pattern:**
- **Bronze Layer**: Raw data ingestion from CSV files
- **Silver Layer**: Clean dimension tables with business logic applied
- **Gold Layer**: Optimized fact tables for analytics and reporting
- **Technologies**: Azure Databricks, Delta Lake, PySpark

## My Implementation Journey

- **Step 1: Data Analysis & Schema Design6**
- First, I analyzed the business requirements and designed a star schema to support key analytics:
- **1,946,573** payment transactions analyzed
- **74,999** unique rider profiles
- **837** bikeshare stations

## Key Results

- **4,584,706** trip records processed
- **1,946,573** payment transactions analyzed
- **74,999** unique rider profiles
- **837** bikeshare stations

## Technologies Used

- Azure Databricks
- Delta Lake  
- Apache Spark
- Python/PySpark
- Star Schema Design

## Getting Started

Execute notebooks in order:
1. Extract bronze layer data
2. Create dimension tables
3. Build fact tables  
4. Run analytics queries

---

Built for data-driven insights into urban mobility patterns
