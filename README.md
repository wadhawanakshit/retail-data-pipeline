# retail-data-pipeline
# 🛍️ E-Commerce Sales, Data Cleaning & SQL Intelligence Pipeline

## Project Overview
An end-to-end data analytics and automated reporting project designed to ingest raw transactional logs, clean data anomalies, run relational SQL queries for core business metrics, and generate executive-ready reports. Built using Python, Pandas, SQLite, and Google Colab.

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Data Processing & Validation:** Pandas, NumPy
* **Database & Queries:** SQLite3, SQL (Aggregations, `CASE WHEN`, Group By)
* **Reporting:** Openpyxl (Excel Automation)
* **Environment:** Google Colab

---

## ⚙️ Key Technical Features
1. **Data Quality & Validation Audit:** 
   * Handled duplicate tracking IDs and missing customer values.
   * Standardized messy categorical text strings (fixed capitalization and trailing spaces in city names).
   * Filtered out corrupted negative quantities and engineered net revenue metrics.
2. **Relational SQL Analytics:** 
   * Loaded the processed dataframe into an in-memory SQLite database.
   * Executed multi-table queries to analyze monthly revenue trends, category return rates, and top-performing cities.
3. **Automated Executive Reporting:** 
   * Compiled aggregated dataframes into a structured, multi-tab Excel workbook (`ecommerce_executive_summary.xlsx`) using Python scripts.

---

## 📊 Key Business Insights Discovered
* **Revenue Drivers:** Electronics and Fashion drive over 55% of gross revenue, with high transaction volumes in major urban hubs like Delhi and Bengaluru.
* **Operational Quality:** Identified a ~10% return rate across specific categories, flagging potential areas for inventory and product quality audits.
