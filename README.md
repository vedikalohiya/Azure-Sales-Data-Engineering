🚀 Azure Sales Data Engineering Project
📌 Overview

This project demonstrates an end-to-end data engineering pipeline using PySpark to process and transform e-commerce sales data.

⚙️ Tech Stack
Python
PySpark
Apache Spark
Power BI
Azure (Architecture)
🏗️ Architecture
Raw Data (CSV)
     ↓
Bronze Layer (Raw Ingestion)
     ↓
Silver Layer (Data Cleaning & Transformation)
     ↓
Gold Layer (Analytics Ready Data)
     ↓
Power BI Dashboard
🔥 Key Transformation
df = df.withColumn("revenue", col("price") + col("freight_value"))
📂 Project Structure
archive/                → Raw datasets
Data_Bricks-Notebooks/ → PySpark notebooks
PowerBI files/         → Dashboards
📊 Features
Data ingestion from raw CSV files
Data transformation using PySpark
Revenue calculation
Layered data architecture
Analytics-ready dataset
🎯 Outcome
Processed structured dataset
Improved data quality
Ready for visualization & insights
