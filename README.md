# Power BI and SQL Sales Analysis Project

This project performs sales analysis using SQL Server for data preparation and Power BI for interactive visualizations. The aim is to provide clear insights into sales performance and trends.

## Project Overview

This repository contains SQL scripts for ETL, cleaned datasets for dimensional modeling, and Power BI reports for sales analysis.

## Key Features

*   **Data Cleaning & Transformation**: SQL Server for star schema creation.
*   **Dimensional Modeling**: Implements `DIM_Calendar`, `DIM_Customer`, `DIM_Products`, and `FACT_InternetSales`.
*   **Sales Performance Analysis**: Provides insights into sales trends and performance.
*   **Interactive Visualizations**: Power BI dashboards for stakeholders.
*   **Historical Data**: SQL queries pull the last two years of sales data for analysis.

## Technologies Used

*   **SQL Server**: Data storage, ETL, and data warehousing.
*   **Power BI**: Data visualization and reporting.

## Data Source

The `AdventureWorksDW2019` database, specifically `[AdventureWorksDW2019].[dbo].[FactInternetSales]` and related dimensions.

## Project Structure

*   `cleaning and transformation/`: Data cleaning scripts.
*   `data/`: SQL scripts for dimensional and fact tables (e.g., [data/DIM_Calendar.sql](data/DIM_Calendar.sql), [data/DIM_InternetSales.sql](data/DIM_InternetSales.sql)).
*   `notebooks/`: Jupyter notebooks for exploration.
*   `reports/`: Power BI report files (.pbix).
*   `src/`: Additional source code.
*   `tests/`: Unit and data validation tests.

## Setup and Usage

1.  **SQL Server Setup**:
    *   Connect to a SQL Server instance with the `AdventureWorksDW2019` database.
    *   Execute SQL scripts in the [data/](data/) directory to create the dimensional model.

2.  **Power BI Integration**:
    *   Open Power BI Desktop and connect to your SQL Server database.
    *   Import tables (`DIM_Calendar`, `DIM_Customer`, `DIM_Products`, `FACT_InternetSales`) and build relationships.
    *   Develop visualizations or use existing reports from [reports/](reports/).

3.  **Data Refresh**:
    *   SQL queries are designed to fetch recent data (e.g., last two years).
    *   Configure Power BI Service for scheduled refreshes.

## Contributing

Please refer to the [LICENSE](LICENSE) for contribution guidelines.


## Contact

Frank Ohene-Darkoh - ohenedarkohfrank@gmail.com - https://www.linkedin.com/in/frankohene-darkoh-44412222b
