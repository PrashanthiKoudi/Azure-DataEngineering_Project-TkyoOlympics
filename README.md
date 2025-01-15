# Tokyo Olympics Data Pipeline

This repository implements a scalable data pipeline for analyzing and visualizing data related to the Tokyo Olympics. Using Azure cloud services, the pipeline enables seamless data integration, transformation, analytics, and visualization.

---

## Architecture Overview

The pipeline is divided into the following stages:

1. **Data Integration**
   - Ingest data from various sources using **Azure Data Factory**.
   - Store raw data in **Azure Data Lake Gen2**.

2. **Data Transformation**
   - Process and clean data using **Azure Databricks**.
   - Store transformed data back in **Azure Data Lake Gen2**.

3. **Analytics**
   - Analyze and model data using **Azure Synapse Analytics**.

4. **Visualization**
   - Create dashboards with:
     - **Power BI**
---

## Features

- End-to-end ETL pipeline for Tokyo Olympics data.
- Scalable processing with Spark on Databricks.
- Advanced analytics with Azure Synapse.
- Rich and interactive dashboards for data visualization.

## Requirements

- **Azure Subscription** (Data Factory, Data Lake, Databricks, Synapse Analytics)
---
