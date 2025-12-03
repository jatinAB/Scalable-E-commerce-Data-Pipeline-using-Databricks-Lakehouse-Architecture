# 📦 Scalable E-commerce Data Pipeline using Databricks Lakehouse

An end-to-end data engineering project built on **Databricks Free Edition**, leveraging **PySpark**, **Delta Lake**, and the **Medallion Architecture (Bronze–Silver–Gold)** to process, clean, and transform e-commerce datasets into analytics-ready tables.

---

## 🚀 Project Overview

This project rebuilds a non-scalable Python ETL into a **distributed, fault-tolerant Lakehouse pipeline**.
It ingests raw e-commerce data, applies validation & enrichment, generates curated Gold tables, and enables business insights through BI dashboards.

---

## 🏛️ Architecture

### **Medallion Layers**

* **Bronze:** Raw ingestion of orders, products, customers (CSV).
* **Silver:** Cleaning, normalization, deduplication, type corrections.
* **Gold:** Business transformations — regional mapping, weekend flags, financial metrics (Gross, Discount, Net Sales).

### **Core Technologies**

* Databricks Community Edition
* Apache Spark (PySpark)
* Delta Lake (ACID, Time Travel)
* Unity Catalog
* SQL Analytics / BI Dashboard

---

## 🔧 Key Features

* Distributed ETL with PySpark
* Currency standardization to INR
* Delta tables with versioning
* Performance optimization using repartition/coalesce
* Automated transformations with SQL + PySpark
* Interactive BI dashboard (sales trends, category insights, heatmaps)

---

## 📊 Output Artifacts

* **Bronze Tables:** Raw loaded data
* **Silver Tables:** Clean & validated datasets
* **Gold Tables:**

  * Sales summary
  * Revenue by category
  * Region-wise performance
  * Monthly trends

---

## ▶️ How to Run

1. Create a free **Databricks Community Edition** account.
2. Import the notebooks into your workspace.
3. Upload the dataset in `/data`.
4. Run notebooks in order: Bronze → Silver → Gold.
5. Use SQL editor to generate dashboard visualizations.

---

## 🛡️ License

This project is released under the **MIT License**, allowing anyone to use, modify, and share it.

---

## 🙌 Contributions

Pull requests are welcome. For major changes, please open an issue first.

---

## 🌟 Author

**Jatin Bandekar**
📍 Thane, India

---
