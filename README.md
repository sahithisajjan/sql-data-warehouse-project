# sql-data-warehouse-project
building a modern data warehouse with SQL server, including ETL processes, data modeling, and data analytics.
# Data Warehouse and Analytics Project

## 👋 About This Repo

A complete data warehouse built from raw CSVs to a business-ready star schema and analytics layer — covering ETL, data cleansing, dimensional modeling, and SQL-based reporting. Built as a hands-on project to practice the full data engineering + analytics pipeline end-to-end.

---

## 🎯 What I Practiced

Building this project gave me hands-on experience with:
- Designing and implementing **Medallion Architecture** (Bronze / Silver / Gold layers)
- Writing **ETL pipelines** in SQL to extract, clean, and load data from CRM and ERP sources
- **Data cleansing and standardization** — handling nulls, duplicates, inconsistent formats
- **Dimensional modeling** — building fact and dimension tables in a star schema
- Writing **analytical SQL queries** to answer real business questions about customer behavior, product performance, and sales trends
- Working with **SQL Server** end-to-end as both a database engine and reporting layer

---

## 🏗️ Data Architecture

The project follows Medallion Architecture with **Bronze**, **Silver**, and **Gold** layers:

1. **Bronze Layer** — Raw data ingested as-is from CSV source files into SQL Server.
2. **Silver Layer** — Cleaned, standardized, and normalized data ready for modeling.
3. **Gold Layer** — Business-ready star schema optimized for reporting and analytics.

---

## 📂 Repository Structure

```
data-warehouse-project/
│
├── datasets/                # Raw CRM and ERP source data (CSV)
├── docs/                    # Architecture diagrams and documentation
├── scripts/
│   ├── bronze/               # Raw ingestion scripts
│   ├── silver/                # Cleaning and transformation scripts
│   ├── gold/                  # Star schema / analytical model scripts
├── tests/                    # Data quality checks
├── README.md
└── LICENSE
```

---

## 🧠 Key Takeaways



---

## 🙏 Credit

Original project design by [Data With Baraa](https://linkedin.com/in/baraa-khatib-salkini). Licensed under [MIT License](LICENSE).
