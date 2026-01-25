**Spotify Azure Data Engineering Project**
This repository contains an end-to-end data engineering project built on Microsoft Azure using data from the Spotify API. The project focuses on designing a practical data pipeline that handles data ingestion, transformation, and storage using cloud-native services.
The goal of this project is to understand how real data pipelines are built and managed in a production-style environment while working with commonly used Azure tools.

**Project Overview**
The pipeline begins by extracting data from the Spotify API and storing it in Azure Data Lake as raw data. Azure Data Factory is used to automate and orchestrate the ingestion process. The raw data is then processed and transformed using PySpark in Azure Databricks. After transformation, the data is stored in a structured format that can be used for analytics, reporting, or further processing.
This project follows a layered data approach to keep raw and processed data separate and easy to manage.

**Architecture Flow**
Spotify API provides raw data
Azure Data Factory handles data ingestion
Azure Data Lake Gen2 stores raw and processed data
Azure Databricks (PySpark) performs data cleaning and transformation
Final datasets are ready for analytics or BI use

**Key Features**
Automated data ingestion using Azure Data Factory
Scalable storage with Azure Data Lake Gen2
Data transformation using PySpark in Azure Databricks
Clear separation of raw and transformed data
Clean project structure and reusable code
Designed to reflect real-world data engineering practices

**Technologies Used**
Azure Data Factory
Azure Data Lake Storage Gen2
Azure Databricks
PySpark
Python
Spotify API
Git & GitHub

**Repository Structure**.
├── adf_pipeline/          
├── databricks/           
├── data/                 
├── configs/              
├── docs/                 
└── README.md


**Purpose of This Project**
This project was built to improve hands-on skills in data engineering and cloud technologies. It demonstrates how data flows through a modern Azure-based pipeline and serves as a portfolio project for data engineering roles.

