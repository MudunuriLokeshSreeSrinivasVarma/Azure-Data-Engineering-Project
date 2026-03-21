## **Data Engineering Project – Hospital Data Pipeline**
# **Overview**

This repository contains the code and documentation for a data engineering project that processes and analyzes hospital data. The project leverages multiple Azure services, including Azure Data Factory, Azure Data Lake Storage Gen2, Azure Databricks, and Azure SQL Database, to build a scalable data pipeline. The processed data is then visualized using Microsoft Power BI to generate business insights.

# **Project Structure**
**data_factory:** Contains the Azure Data Factory configuration files and data pipeline definitions.
**databricks:** Contains PySpark code and notebooks used for data transformation.
**synapse_analytics**: Includes SQL scripts and notebooks for data analysis in Azure Synapse Analytics.
**power_bi:** Contains Power BI reports and datasets for data visualization.

# Project Steps
**Data Ingestion:** Data from Kaggle is stored in a storage container in a specific Azure Storage account.

**Data Factory:** An Azure Data Factory is deployed to create data pipelines. These pipelines retrieve data from GitHub, perform transformations, and store the results in Data Lake Gen 2.

**Azure Databricks:** Azure Databricks is used to run PySpark code for data transformation. The data storage is mounted to the Data Factory for seamless data access.

**Data Transformation:** PySpark scripts in Databricks transform the data, and the results are returned to the storage container.

**Azure SQL Database:** Azure Synapse Analytics is deployed for SQL data analysis. Data is loaded into Synapse Analytics for complex analytical queries.

**Data Visualization:** The data is loaded into Microsoft Power BI for creating interactive dashboards and reports.

# Dashboards Created

Executive Overview
Doctor Performance
Treatment Analytics
Patient Billing Insights
Appointment Analysis

# Usage

Run the data pipelines using Azure Data Factory to retrieve, transform, and store the data.

Execute the PySpark scripts in Azure Databricks for further data transformation.

Utilize Azure SQL Database using SQLServer for SQL queries.

Load the data into Microsoft Power BI to create visualizations and reports and add tables and different measures.

# Dependencies
Azure Data Factory
Azure Data Lake Storage Gen2
Azure Databricks
Azure SQL Database
Microsoft Power BI
PySpark
SQL

# Credits
Hospital Data Source: https://www.kaggle.com/datasets/kanakbaghel/hospital-management-dataset
