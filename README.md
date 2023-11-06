# Azure Databricks Synapse Integration

This repository contains the code and resources for an end-to-end data engineering project in the Azure cloud environment. The project involves ingesting raw data from a source into Azure Data Lake Storage Gen2 using Azure Data Factory, performing data transformations in Azure Databricks, and using Azure Synapse Analytics for data analysis and dashboard creation.

## Architecture
![Azure Synapse project](https://github.com/qadeerbangash/azure-dataFactory-databricks-pipeline/assets/64665560/e6c1c35d-384b-4a2c-a399-d46ac0ff6c6e)

## Project Overview

The project can be divided into the following key components:

1. **Azure Data Factory (ADF):**
   - ADF is used to create data pipelines that copy raw data from a source into Azure Data Lake Storage Gen2. The raw data is ingested and stored for further processing.

2. **Azure Databricks:**
   - Azure Databricks is utilized for data processing and transformation. PySpark code is written to perform various transformations on the raw data. Processed data is then written back to the Data Lake Gen2.

3. **Azure Synapse Analytics:**
   - Azure Synapse Analytics is employed for data analysis. SQL queries are used to extract insights and generate reports from the transformed data.

4. **Dashboard Creation:**
   - The insights gained from Azure Synapse Analytics are used to build interactive dashboards for data visualization and reporting.

## Getting Started

To get started with this project, follow these steps:

1. Clone this repository to your local environment.

2. Review the code in the respective folders to understand how data pipelines, transformations, and data analysis are performed.

3. Set up the necessary Azure resources and services as described in the project documentation.

4. Run the data pipelines in Azure Data Factory to ingest raw data.

5. Execute the PySpark code in Azure Databricks to perform data transformations.

6. Use Azure Synapse Analytics to run SQL queries and extract insights from the data.

7. Create and customize dashboards for data visualization.

## Project Structure

The project structure is organized as follows:

- `/data-factory`: Contains Azure Data Factory related files and configurations.
- `/databricks`: Includes PySpark code for data transformation in Azure Databricks.
- `/synapse-analytics`: Contains SQL queries and scripts for data analysis in Azure Synapse Analytics.

## Requirements

- Azure subscription and access to Azure Portal.
- Azure Data Factory.
- Azure Databricks.
- Azure Data Lake Storage Gen2.
- Azure Synapse Analytics.

## Acknowledgments

- Special thanks to Microsoft Azure for providing the tools and services for this project.


