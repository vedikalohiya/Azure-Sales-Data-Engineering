# 🚀 Azure Sales Data Engineering Project

## 📌 Problem Statement

Organizations often deal with **fragmented sales data** across multiple systems, making it difficult to perform **real-time analytics and decision-making**.

This project builds a **scalable data pipeline** to:

* Ingest raw transactional data
* Clean and transform it
* Produce analytics-ready datasets

---

## 🎯 Solution

Designed an **end-to-end Data Engineering pipeline** using **PySpark**, following the **Medallion Architecture (Bronze → Silver → Gold)**.

```text
Raw CSV → Bronze → Silver → Gold → Power BI
```

---

## 🏗️ Architecture

* **Bronze Layer**: Raw ingestion from CSV (no transformation)
* **Silver Layer**: Data cleaning, schema enforcement, feature engineering
* **Gold Layer**: Aggregated, analytics-ready data for reporting

---

## 🛠️ Tech Stack

* Python
* PySpark
* Azure Data Engineering Concepts
* Power BI
* Jupyter Notebook / VS Code

---

## ⚙️ Key Transformations

* Revenue calculation:

```python
df = df.withColumn("revenue", col("price") + col("freight_value"))
```

* Schema inference and standardization
* Timestamp handling and formatting
* Data cleaning for null and inconsistent values

---

## 📊 Output

* Clean, structured dataset
* Revenue metrics generated
* Ready for dashboarding in Power BI

---

## 📈 Business Impact

* Enables **faster reporting and analytics**
* Converts raw data into **decision-ready insights**
* Mimics real-world **data lake architecture used in enterprises**

---

## 🧠 Engineering Highlights

* Implemented **layered data architecture**
* Designed transformations using **distributed processing (PySpark)**
* Built pipeline that can scale to **large datasets**
* Modular notebook structure for easy extension

---

## 📂 Project Structure

```
Azure-Sales-Data-Engineering/
│
├── archive/                        # Raw datasets
├── Data_Bricks-Notebooks/         # PySpark notebooks
├── PowerBI files/                 # Dashboard
├── Dataset/
└── README.md
```

---

## 🚀 How to Run

```bash
git clone https://github.com/vedikalohiya/Azure-Sales-Data-Engineering.git
cd Azure-Sales-Data-Engineering

python -m venv .venv
.venv\Scripts\activate

pip install pyspark jupyter
```

Run:

```
bronze to silver.ipynb
```

---

## 🔮 Future Enhancements

* Azure Data Factory for orchestration
* Azure Data Lake Storage integration
* Real-time streaming (Event Hub)
* Databricks deployment

---

## 💼 Resume Highlights (Key Points)

* Built an end-to-end data pipeline using PySpark and Medallion architecture
* Transformed raw sales data into analytics-ready datasets
* Implemented feature engineering including revenue calculation
* Designed scalable data processing workflows

---

## 👩‍💻 Author

Vedika Lohiya

---

⭐ Star this repo if you found it useful!
