# Medallion-Architecture
This pipeline demonstrates a Medallion Architecture workflow in Microsoft Fabric, moving from raw ingestion to processed data and finally to semantic models for reporting

## Workflow Overview

![Data Workflow](Data%20Workflow.png)

## Student Pipeline Workflow
### 1️⃣ Lakehouse
ingestion of the raw data into fabric
![Student Lakehouse](workflow/student_lakehouse.png)

### 2️⃣ Pipeline
building of pipelines
![Student Pipeline](workflow/student_pipeline.png)

### 3️⃣ Data Warehouse
loading of the structured data into the data warehouse
![Student Warehouse](workflow/student_warehouse.png)

### 4️⃣ Semantic Model
creating a semantic model to be used for visualization in Power BI
![Student Semantic Model](workflow/Student%20Sementic%20Model.png)
