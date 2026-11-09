# DataNexis – Restaurant Data Engineering & Analytics

## Project Overview

DataNexis is an end-to-end restaurant data engineering and analytics capstone project developed using Microsoft Azure Databricks. It focuses on data ingestion, transformation, processing and analytics to generate meaningful business insights.

## Architecture

This project implements the Medallion Architecture:

- **Bronze Layer:** Raw data ingestion.
- **Silver Layer:** Data cleaning and transformation.
- **Gold Layer:** Business-level analytical tables and insights.

## Technologies Used

- Microsoft Azure Databricks
- Databricks SQL
- Delta Lake
- Delta Live Tables
- SQL
- GitHub

## Key Features

- Data ingestion using Databricks.
- Incremental data loading using COPY INTO.
- Data cleaning and transformation.
- Bronze, Silver and Gold data layers.
- Streaming tables and materialized views.
- Restaurant performance analysis.
- Interactive analytical dashboards.

## Dashboard Insights

The project includes visualizations for:

- Total orders per restaurant.
- Item-wise quantity sold.
- Daily revenue trends.
- Overall revenue KPI.

**Dashboard revenue KPI:** 6,578,871 (as displayed in the project dashboard).

## Repository Structure

```text
DataNexis/
├── notebooks/
│   ├── VighneshwarReddy_Capstone.ipynb
│   └── Dine_PL.ipynb
├── screenshots/
│   ├── dashboard/
│   └── pipeline/
└── README.md
```

## Project Outcomes

- Implemented a multi-layer data engineering pipeline.
- Developed analytical datasets for restaurant business insights.
- Created visualizations to support data-driven decisions.

## Author

**Vighneshwar Reddy**

## Project Category

Data Engineering | Data Analytics | Capstone Project

## Project Screenshots

### Databricks Analytics Dashboard
![Dashboard](screenshots/dashboard.png)

### Data Engineering Pipeline
![Pipeline](screenshots/pipeline.png)
