# 🚀 Azure Sales Data Engineering Project

## 📌 Project Overview

This project demonstrates an **end-to-end Data Engineering pipeline** built using **PySpark and Azure-based architecture concepts**.

The goal is to transform raw sales data into **analytics-ready datasets** using a **Medallion Architecture (Bronze → Silver → Gold)**.

---

## 🏗️ Architecture

The project follows a layered data architecture:

```
Raw CSV Data → Bronze Layer → Silver Layer → Gold Layer → Power BI Dashboard
```

### 🔹 Bronze Layer (Raw Ingestion)

* Raw data is ingested from CSV files
* Stored without transformation

### 🔹 Silver Layer (Data Cleaning & Transformation)

* Data cleaning and type casting
* Feature engineering (e.g., revenue calculation)
* Schema standardization

### 🔹 Gold Layer (Analytics Ready)

* Aggregated and business-ready datasets
* Used for reporting and dashboards

---

## 🛠️ Tech Stack

* **Python**
* **PySpark**
* **Azure Data Engineering Concepts**
* **Power BI**
* **VS Code & Jupyter Notebook**

---

## 📂 Project Structure

```
Azure-Sales-Data-Engineering/
│
├── archive/                        # Raw datasets (CSV files)
├── Data_Bricks-Notebooks/         # PySpark notebooks
│   ├── bronze to silver.ipynb
│   ├── silver to gold.ipynb
│   └── storagemount.ipynb
│
├── PowerBI files/                 # Dashboard files
├── Dataset/                       # Additional datasets
├── README.md
```

---

## 🔄 Key Transformation

Example: Revenue C
