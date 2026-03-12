# Databricks-E-commerce-Data-Engineering-Project

📌 Project Overview
This project demonstrates an end-to-end data engineering pipeline built on Databricks using PySpark, Python, and SQL. The objective was to ingest large volumes of e-commerce data, clean and transform it, and organize it into a medallion architecture (Bronze, Silver, Gold) for analytics and business intelligence.


⚙️ Technologies Used : 
Databricks,PySpark,Python,SQL,Delta Lake,Data Pipeline Architecture,Data Cleaning & Transformation,Dashboard Visualization (Genie)


🏗️ Architecture: This project follows the Medallion Architecture:
Bronze Layer :
1.) Raw data ingestion from multiple CSV files 2.) Data stored in raw format 3.) Handles large volume datasets

Silver Layer :
1.) Data cleaning and transformation 2.) Handling null values, duplicates 3.) Standardizing schema

Gold Layer :
1.) Business-level aggregated data 2.) Creation of dimensional model 3.) Data prepared for analytics and dashboarding


🔄 Data Pipeline Workflow :
STEP 1: Ingest bulk e-commerce CSV data into Databricks.
STEP 2: Store raw data in Bronze Layer.
STEP 3: Clean and transform data using PySpark.
STEP 4: Move processed data into Silver Layer.
STEP 5: Create Gold Layer dimensional tables for analytics.
STEP 6: Build dashboards using Databricks Genie.


🚀 Key Features:
1.) Large dataset ingestion using Databricks
2.) Data processing using PySpark
3.) Implementation of Medallion Architecture
4.) Creation of analytics-ready Gold Layer
5.) Dashboard generation for business insights


📈 Use Case: The processed dataset can help analyze:
Sales trends , Customer purchase behavior , Product performance , Revenue insights
