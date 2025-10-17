# 🏒 NHL Game Analytics — Data Engineering Project

## 📖 Summary
The **NHL Game Analytics Project** is an end-to-end **data engineering solution** built on **Microsoft Fabric**, a unified SaaS platform that provides a **one-stop solution** for data ingestion, transformation, storage, and visualization.  It streamlines the NHL data workflow from raw Kaggle datasets to Power BI dashboards, enabling structured and scalable insights into player, goalie, and team performance.

---

## 📊 Data Source
- **Source:** [NHL Game Data — Kaggle Dataset](https://www.kaggle.com/datasets/martinellis/nhl-game-data)  
- **Format:** 13 CSV files → 8 cleaned and validated tables for analysis

---

## ⚙️ Tech Stack
- **Platform:** Microsoft Fabric (Lakehouse + Notebooks + Power BI)  
- **Compute:** PySpark  
- **Storage:** OneLake (Delta Tables)  
- **Visualization:** Power BI  

---

## 🔁 Pipeline Workflow
**Bronze → Silver → Gold Architecture**
1. **Bronze:** Ingest raw NHL data from Kaggle  
2. **Silver:** Clean, standardize, and validate with PySpark  
3. **Gold:** Create analytics-ready fact & dimension tables for Power BI  

---

## 🧩 Data Modeling
- **Design:** Galaxy Schema (shared dimensions for multiple fact tables)  
- **Approaches:**  
  - *Silver Layer* – Real-time KPI flexibility  
  - *Gold Layer* – Pre-aggregated metrics for faster dashboards  

---

## 🚀 Future Improvements
- Automate the pipeline for end-to-end data refresh and scheduling  

---

## 🧠 Skills Demonstrated
- Data Engineering  
- PySpark ETL  
- Delta Tables  
- Microsoft Fabric Lakehouse  
- Data Modeling (Star/Galaxy Schema)  
- Power BI Semantic Modeling  
- Medallion Architecture Implementation  
