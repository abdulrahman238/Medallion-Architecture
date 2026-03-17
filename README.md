# Medallion-Architecture
This pipeline demonstrates a Medallion Architecture workflow in Microsoft Fabric, moving from raw ingestion to processed data and finally to semantic models for reporting

## Workflow Overview

![Data Workflow](Data%20Workflow.png)

## Student Pipeline Workflow

### 1️⃣ Lakehouse
ingestion of the raw data into fabric
![Student Lakehouse](workflow/student_lakehouse.png)

### 2️⃣ Pipeline
buiding of piplines 
![Student Pipeline](workflow/student_pipeline.png)

### 3️⃣ Data Warehouse
loading of the stured data into the data warehouse
![Student Warehouse](workflow/student_warehouse.png)

### 4️⃣ Semantic Model
creating a sementic model to be used for visaulisation in power bi
![Student Semantic Model](workflow/Student_Sementic_Model.png)
