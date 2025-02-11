# Azure Data Pipeline Project

## Overview

This project demonstrates the creation of a data pipeline leveraging various Azure services for ingestion, storage, analysis, and visualization of external sports data from SportsData.io. The solution automates cloud infrastructure deployment and data transformation using Python while handling JSON and line-delimited JSON (JSONL) formats.

## Architecture

The data pipeline consists of the following key components:

1. **Data Source:**
   - External API: SportsData.io provides the raw data.

2. **Orchestration Layer:**
   - **Ingestion:** Blob Storage ingests the external sports data.
   - **Data Transformation:** JSON data is converted to JSONL format to optimize data storage and query performance.
   - **Storage:** Data is stored in Azure Synapse Analytics.

3. **Analysis Layer:**
   - Azure Analysis Services are used for querying and processing the data.

4. **Visualization Layer:**
   - Power BI provides comprehensive visual reporting of the data.

## Key Features

- **Data Ingestion:** Automates data extraction from an external API.
- **Data Transformation:** Converts JSON to JSONL format for efficient storage.
- **Infrastructure Automation:** Automates cloud infrastructure setup using Python.
- **Data Analysis and Visualization:** Enables insights through Azure Analysis Services and Power BI.

## What We Learned

1. **Creating Data Pipelines with Azure Services:**
   - Utilized Azure Blob Storage for scalable data ingestion.
   - Managed and optimized data queries with Azure Synapse Analytics.
   - Built actionable insights with Azure Analysis Services.

2. **Automating Cloud Infrastructure with Python:**
   - Automated deployment of cloud resources.
   - Enhanced efficiency and reliability through code-driven infrastructure management.

3. **Handling JSON and JSONL Formats:**
   - Learned best practices for converting JSON to JSONL.
   - Improved data storage efficiency and analysis speed.

## Tools and Technologies Used

- **Cloud Provider:** Microsoft Azure
- **Services:** Azure Blob Storage, Azure Synapse Analytics, Azure Analysis Services
- **Programming Language:** Python
- **Data Format:** JSON, JSONL
- **Visualization Tool:** Power BI
- **External API:** SportsData.io

## Conclusion

This project provides a comprehensive guide for building automated data pipelines in Azure, leveraging modern cloud services for efficient data ingestion, transformation, storage, analysis, and visualization.
