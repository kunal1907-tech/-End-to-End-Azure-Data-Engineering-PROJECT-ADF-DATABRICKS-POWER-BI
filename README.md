# End-to-End-Azure-Data-Engineering-PROJECT-ADF-DATABRICKS-POWER-BI
Azure Data Engineering Project ! Implement Medallion Architecture using Azure Data Factory (ADF), Azure Databricks, ADLS Gen2, Azure SQL, and Power BI. 
## 🎯 Project Overview

Welcome to the **Azure Data Engineering Project — From Start to Finish!**  
In this project, In This project I demonstrated a real-time data pipeline that ingests, transforms, and visualizes customer engagement metrics from multiple retail stores. It uses the Medallion Architecture (Bronze, Silver, Gold) to ensure scalable and clean data layers.

- **Azure Data Factory (ADF)** — For data orchestration & ETL pipelines  
- **Azure Databricks** — For scalable data transformation & analytics  
- **Azure Data Lake Storage Gen2 (ADLS)** — For data lake storage  
- **Azure SQL Database** — For the curated serving layer  
- **Power BI** — For building interactive business dashboards

### 🧮 Project Steps (Start → Finish)

1.Provision Azure Resources
Create ADF, Databricks workspace, ADLS Gen2, Azure SQL, and Power BI workspace.

2.Ingest Data (Bronze Layer)
Use ADF Copy Activity to pull raw data from sources (CSV, API, Database) into ADLS Gen2.

3.Transform Data (Silver Layer)
Use Databricks (PySpark) to clean, standardize, and deduplicate the ingested data.

4.Aggregate Data (Gold Layer)
Apply business logic, aggregations, and KPIs in Databricks and save to the Gold layer.

5.Load to Azure SQL
Push Gold data into Azure SQL Database for serving and reporting.

6.Visualize in Power BI
Connect Power BI to Azure SQL → build dashboards → publish to Power BI Service.

#### ⚙️ Core Azure Components 

| Service                      | Role           | Description                                           |
| ---------------------------- | -------------- | ----------------------------------------------------- |
| **ADF (Azure Data Factory)** | Orchestration  | Ingests data from multiple sources into ADLS          |
| **ADLS Gen2**                | Storage        | Stores raw, cleaned, and curated data layers          |
| **Databricks**               | Transformation | Executes PySpark-based transformations & aggregations |
| **Azure SQL**                | Serving Layer  | Hosts processed, query-ready data for analytics       |
| **Power BI**                 | Visualization  | Connects to Azure SQL and builds business dashboards  |

##### 🛠️ *TECH STACK USED*:  
Azure Data Factory (ADF)  
Azure Databricks (PySpark, Delta Lake)  
Azure Data Lake Storage  
Azure SQL Database  
Power BI (DAX, Data Modeling)  
Medallion Architecture Framework
