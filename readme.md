# End-to-End Ride Analytics using Azure Data Factory and Databricks

## Overview
Delta Lake is an open-source storage layer designed by Databricks, the company behind Apache Spark, to enhance existing data lakes. It provides ACID transactions, data versioning, and other advanced features to address limitations in traditional data lakes for big data processing. 

## Objective

- This project aims to implement analytics/insights on trip transactions and ride-based source data from SQL Server using a `Medallion Architecture` approach. 

- The implementation involves Azure Data Factory (ADF), Azure Blob Storage (ADLS Gen2), and Azure Databricks for data ingestion, transformation, and loading into Delta tables.

---

## Tech Stack
- **Language:** `Python`, `SQL`, `Spark`
- **Package:** `PySpark`
- **Services:** `Azure Data Factory (ADF)`, `Azure Blob Storage (ADLS Gen2)`, `Azure Databricks`, `Logic Apps`, `Azure SQL Database`

---

## Key Benefits of Delta Lake
- **ACID transactions:** Ensures atomicity, consistency, isolation, and durability for data lake tables.
- **Data versioning:** Enables versioning of data, facilitating tracking and reverting to previous versions.
- **Schema enforcement:** Enforces schema on write for clean and consistent data.
- **Time travel:** Allows time travel queries, querying data as it existed at a specific point in time.
- **Faster queries:** Optimizes query performance and reduces latency through advanced indexing and caching.

Delta Lake is compatible with Apache Spark and can be used with various big data tools, often integrated with cloud storage services like Amazon S3 or Azure Data Lake Storage.

---

## Azure Data Factory (ADF)
- Azure Data Factory is a cloud-based data integration service on the Azure platform. 
- It facilitates the creation, scheduling, and orchestration of data workflows for ingesting, preparing, transforming, and moving data across various sources and destinations.

---

## Azure Databricks
- Azure Databricks is a cloud-based big data and analytics service powered by Apache Spark. 
- It offers a collaborative workspace for data scientists, engineers, and analysts to process, analyze, and visualize large datasets using Spark's distributed computing capabilities.

---

## Logic Apps
- Azure Logic Apps automates business processes and integrates with different systems and services. 
- It provides a visual designer and various connectors, enabling workflow creation without coding for both technical and non-technical users.

---
