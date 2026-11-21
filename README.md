# Buy Anything Sales – Data Engineering Project

## Project Overview
This is an end-to-end Data Engineering project built using Microsoft Azure services. The project processes sales data and organizes it into Bronze, Silver, and Gold layers.

## Technologies Used
- Azure Data Factory (ADF)
- Azure SQL Database
- Azure Data Lake Storage Gen2 (ADLS)
- Azure Databricks
- PySpark
- Delta Lake
- GitHub

## Project Architecture

1. **Source:** Sales data in CSV format.
2. **Data Ingestion:** Azure Data Factory pipelines.
3. **Source Database:** Azure SQL Database.
4. **Bronze Layer:** Raw data storage in ADLS Gen2.
5. **Silver Layer:** Data cleaning and transformation using PySpark.
6. **Gold Layer:** Dimension and Fact tables.

## Gold Layer Tables
- dim_customer
- dim_date
- dim_product
- dim_region
- dim_factsales

## Project Objectives
- Build automated data ingestion pipelines.
- Implement data transformation using PySpark.
- Organize data using Medallion Architecture.
- Create dimension and fact tables.
- Implement incremental data processing.

## Author
Raj Dhar

## Project Status
Successfully completed. This project demonstrates end-to-end data ingestion, transformation, and processing using Microsoft Azure services.
