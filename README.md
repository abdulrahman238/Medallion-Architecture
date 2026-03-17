# Medallion-Architecture
This pipeline demonstrates a Medallion Architecture workflow in Microsoft Fabric, moving from raw ingestion to processed data and finally to semantic models for reporting


# Microsoft Fabric Data Pipeline

This repository showcases a **data engineering workflow** built in **Microsoft Fabric**, demonstrating end-to-end ingestion, pipeline processing, and loading into a data warehouse and semantic model.

## Workflow Overview

![Fabric Data Pipeline Workflow](workflow/fabric-data-pipeline-workflow.png)

**Workflow Steps:**

### 1. Ingestion Layer
- **Data Sources:** CSV, Parquet files from local or cloud storage  
- **Lakehouse:** Central storage for raw data  
- **Get Metadata + Filter:** Identify relevant files for processing  

### 2. Processing Layer
- **ForEach Loop:** Iterates over files  
- **Copy Data Activity:** Moves data to warehouse  
- **Data Transformation:** Optional cleaning or preparation  

### 3. Serving Layer
- **Data Warehouse:** Stores processed data  
- **Semantic Model:** Defines relationships for analytics  
- **Reporting / Dashboard:** Power BI or similar reporting tools  

## Sample Data
- `sample_data/customers/` → customer CSV files  
- `sample_data/orders/` → order CSV files  

## SQL Scripts
- `sql/create_tables.sql` → create warehouse tables  
- `sql/sample_queries.sql` → example queries to test data  

## License
MIT License
