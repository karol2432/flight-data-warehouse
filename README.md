# Flight Data Warehouse (Databricks)

## Project Overview
The goal of this project was to design and implement a data warehouse for analyzing flight data in the United States.  
The solution is built using the Medallion Architecture (Bronze, Silver, Gold) and enables analysis of flight delays, punctuality, and traffic trends.

## Tech Stack
- Databricks (Free Edition)
- Python (PySpark)
- SQL
- Medallion Architecture
- Star Schema
- YAML (Databricks Jobs)

## Data Sources
- flights.csv – flight data  
- airlines.csv – airline information  
- airports.csv – airport information  

## Architecture
The project follows a three-layer architecture:
- **Bronze** – raw data ingestion  
- **Silver** – data cleaning and validation  
- **Gold** – analytical tables and aggregations  

## Key Features
- Incremental data loading  
- Slowly Changing Dimensions (SCD Type 2)  
- Data quality validation and transformations  
- Analytical views and daily aggregations  
- Automated pipeline using Databricks Jobs defined in YAML  

## Automation
The full data pipeline is orchestrated using a Databricks Job described in a YAML configuration file:

