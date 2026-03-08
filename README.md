# Azure End-to-End Data Engineering Project

## Project Overview
This project demonstrates an **end-to-end data engineering pipeline on Microsoft Azure**, designed to ingest, transform, and load data into a scalable analytics platform. 
The pipeline follows a **lakehouse architecture** with Bronze, Silver, and Gold layers for structured data processing.

The goal is to automate data workflows while ensuring **reliability, scalability, and data quality**, making the processed data ready for analytics and reporting.

---

## Architecture
The pipeline leverages the following Azure services:

- **Azure Data Factory** – Orchestrates and schedules ETL workflows  
- **Azure Data Lake Storage** – Stores raw and processed datasets  
- **Azure Databricks** – Performs large-scale data transformations  
- **Azure Synapse Analytics** – Hosts curated data for analytics  
- **Azure Key Vault** – Securely stores credentials and secrets  

![Architecture Diagram](images/architecture.png)  <!-- Upload your diagram here -->

---

## Folder Structure
- `data/` – Raw CSV datasets (Bronze layer)  
- `notebooks/` – Databricks notebooks or Python scripts for transformations  
- `pipelines/` – Azure Data Factory JSON pipeline files  
- `synapse/` – SQL scripts and queries for analytics  
- `images/` – Architecture diagrams, screenshots of pipelines  

---

## Features
- Automated ETL pipelines for batch processing  
- Scalable data transformations using Spark  
- Lakehouse architecture (Bronze → Silver → Gold)  
- Incremental data ingestion and deduplication  
- Monitoring and alerting for pipeline health  

---

## Tech Stack
- **ETL Orchestration:** Azure Data Factory  
- **Data Storage:** Azure Data Lake Storage Gen2  
- **Data Transformation:** Azure Databricks (PySpark)  
- **Analytics / Warehouse:** Azure Synapse Analytics  
- **Security:** Azure Key Vault  

---

## How to Use
1. Clone the repository  
2. Explore CSV files in the `data/` folder  
3. Open notebooks in the `notebooks/` folder for transformation logic  
4. Review ADF JSON pipelines in `pipelines/`  
5. Review SQL scripts in `synapse/`  
6. Refer to architecture and screenshots in `images/`  

---

## Author
[Sitharam] – Data Engineer  
Showcasing
