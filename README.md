# 🚀 SQL Data Warehouse Project

An end-to-end **Data Warehouse project using SQL Server** and **Medallion Architecture (Bronze, Silver, Gold)**.
This project automates the ETL process to transform raw ERP and CRM data into a structured **Gold layer** optimized for business intelligence and reporting.

---
## 🚀 Project Requirements

### 🔹 Data Engineering

**Objective:**
Build a modern data warehouse in SQL Server for analytical reporting.

**Specifications:**

* Import data from ERP and CRM CSV files
* Clean and resolve data quality issues
* Integrate sources into a unified analytical model
* Focus on the latest dataset (no historization required)
* Provide documentation for stakeholders

---

### 🔹 Data Analytics

Develop SQL-based analysis to generate insights on:

* Customer behavior
* Product performance
* Revenue trends over time

---
## 🏗️ Data Architecture

This project follows the **Medallion Architecture** approach:

* **Bronze Layer** → Raw data ingestion from source systems (ERP & CRM CSV files).
* **Silver Layer** → Data cleansing, transformation, and standardization.
* **Gold Layer** → Business-ready data modeled using a Star Schema for analytics and reporting.

📌 Architecture Diagram:
![Data Architecture](docs/data_architecture.png)

---

##  📖 Project Overview

1. **Data Architecture**: Designing a modern Data Warehouse using Medallion Architecture (Bronze, Silver, Gold).
2. **ETL Development**: Building SQL pipelines to ingest, cleanse, and transform ERP & CRM data.
3. **Data Modeling**: Creating optimized fact and dimension tables using a Star Schema.
4. **Analytics & Reporting**: Writing SQL queries to generate actionable business insights.

✅ Key Highlights:
- End-to-end Data Warehousing implementation  
- Data cleaning and transformation  
- Analytical SQL development  
- Business Intelligence concepts  

---


## 🛠️ Tech Stack

* **SQL Server Express**
* **SQL Server Management Studio (SSMS)**
* **CSV Data Sources (ERP & CRM)**
* **Draw.io (Architecture & Modeling)**
* **Git & GitHub**

---



## 📂 Repository Structure

```
sql-data-warehouse-project/
│
├── datasets/                # Raw ERP & CRM CSV files
│
├── docs/                    # Documentation & diagrams
│   ├── data_architecture.drawio
│   ├── data_models.drawio
│   ├── data_flow.drawio
│   ├── data_catalog.md
│   ├── naming-conventions.md
│
├── scripts/
│   ├── bronze/              # Raw data loading scripts
│   ├── silver/              # Data cleaning & transformations
│   ├── gold/                # Star schema & analytical models
│
├── tests/                   # Data validation scripts
│
├── README.md
├── LICENSE
└── .gitignore
```

---

## 🧠 Skills Demonstrated

* Data Warehousing
* ETL Development
* SQL Optimization
* Data Modeling (Star Schema)
* Data Cleaning
* Analytical SQL
* Business Intelligence Concepts

---

## 📌 How to Run This Project

1. Install **SQL Server Express**
2. Install **SQL Server Management Studio (SSMS)**
3. Create a new database
4. Run scripts in the following order:

   * Bronze Layer
   * Silver Layer
   * Gold Layer
5. Execute analytical queries for insights

---

## 🛡️ License

This project is licensed under the MIT License.

---
## 🌟 About Me

Hi, I'm **Akshat** — an aspiring Data Analyst passionate about Data Warehousing, SQL, and Analytics.

I enjoy building end-to-end data projects that transform raw data into meaningful business insights.  
Currently focused on strengthening my skills in:

- SQL & Database Design  
- Data Modeling (Star Schema)  
- ETL Development  
- Business Intelligence & Analytics  

I’m actively building portfolio projects to demonstrate real-world data engineering and analytical capabilities.
