# Customer Data Platform

## Overview

This project demonstrates an end-to-end enterprise data engineering pipeline using Azure Data Factory, Azure Data Lake Gen2, Databricks, PySpark, Snowflake, and Power BI.

## Architecture

Source Systems
      |
      |
Azure Data Factory
      |
      |
Azure Data Lake Gen2
      |
      |
Databricks PySpark Transformation
      |
      |
Snowflake Data Warehouse
      |
      |
Power BI Reporting


## Technologies Used

- Azure Data Factory
- Azure Data Lake Storage Gen2
- Azure Databricks
- PySpark
- Snowflake
- SQL
- Power BI


## Data Flow

1. Ingest customer and transaction data using ADF
2. Store raw files in ADLS Gen2
3. Transform data using Databricks PySpark
4. Load processed data into Snowflake
5. Create analytical models for reporting


## Data Warehouse Model

Dimension Tables:

- DIM_CUSTOMER


Fact Tables:

- FACT_SALES


## Author

Praveen Anthathi

Senior Data Engineer
