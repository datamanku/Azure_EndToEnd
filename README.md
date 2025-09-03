
# End-to-End Azure Data Engineering Pipeline

## Project Overview
This project showcases the design and implementation of an end-to-end Azure data engineering pipeline leveraging Microsoft Azure services including **Azure Data Factory, Azure Data Lake Storage Gen2, Azure Databricks**. The pipeline implements the **Medallion Architecture** (Bronze, Silver, Gold layers) for structured data ingestion, transformation, and analytics readiness.

Data transformations are performed using **PySpark** in Databricks, enabling scalable and efficient processing. Business analytics are powered by integrating **Power BI** dashboards connected to Synapse Analytics, delivering actionable insights.

## Key Features
- Cloud-based data ingestion, transformation, and storage pipeline using Azure services.
- Medallion architecture to organize data layering:  
  - *Bronze Layer:* Raw data ingestion lake  
  - *Silver Layer:* Cleaned and conformed data  
  - *Gold Layer:* Aggregated and business-ready datasets
- Dynamic ETL workflows with PySpark transformations in Azure Databricks.
- Orchestration and monitoring through Azure Data Factory pipelines.
- Integrated business intelligence via Power BI dashboards 

## Tools and Technologies
- **Azure Data Factory** - ETL orchestration and workflow management  
- **Azure Data Lake Storage Gen2** - Scalable cloud storage for raw and processed data  
- **Azure Databricks** - Distributed Apache Spark-based data processing  
- **Power BI** - Interactive visualization and reporting tool  
- **PySpark** - Data transformation and analytics scripting language  
- **VSCode** and **GitHub** - Development environment and version control  

