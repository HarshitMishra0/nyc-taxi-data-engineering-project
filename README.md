# NYC Taxi Data Engineering Project 🚕📊

An End-to-End Azure-based Data Engineering project leveraging:
- **Azure Data Factory** for ingestion using Dynamic Pipelines
- **Azure Databricks** for transformations with PySpark
- **Delta Lake** for ACID-compliant storage
- **Medallion Architecture**: Bronze → Silver → Gold layers
- **Parquet File Format** for optimized big data storage

---

## 📁 Project Structure

- `1_data_ingestion/`: ADF dynamic pipelines and JSON exports
- `2_data_transformation/`: PySpark scripts for processing

---

## ⚙️ Tech Stack

- Azure Data Factory
- Azure Databricks
- PySpark
- Delta Lake
- Parquet
- Medallion Architecture
- Azure Data Lake Storage (Gen2)

---

## 📊 Architecture Overview

![architecture_diagram]
![WhatsApp Image 2025-05-27 at 9 50 39 PM](https://github.com/user-attachments/assets/94669a8d-b472-4bc9-8a37-d4696806fdb3)


---

## 🧠 Key Concepts Covered

- Dynamic pipelines using `ForEach`, `Parameters`, and Linked Services
- API-based data ingestion (no manual uploads)
- PySpark transformations with Delta Lake time travel and versioning
- Medallion architecture best practices
- End-to-end project simulation for interview prep

---

## 📁 Sample Data Flow

`API → ADF → ADLS (Bronze) → Databricks (Silver) → Delta Tables (Gold)`

---

## 📌 How to Run

1. Clone the repo
2. Deploy the ADF JSON to your ADF instance
3. Open Databricks and import notebooks
4. Run the pipeline step by step (Raw → Silver → Gold)

---

## ✅ Status

✅ Completed – Tested on Azure  
🧪 Data Source: NYC Taxi Dataset  
📁 File Format: Parquet + Delta  
