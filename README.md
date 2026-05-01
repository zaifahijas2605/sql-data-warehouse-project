# 📊 SQL Data Warehouse Project

Building a modern **Data Warehouse using SQL Server**, including ETL processes, data modeling, and analytics.

This project demonstrates a complete **data warehousing and analytics solution** — from raw data ingestion to generating actionable insights. It is designed as a **portfolio project** showcasing industry best practices in **data engineering and analytics**.

---

## 🏗️ Data Architecture

This project follows the **Medallion Architecture** approach:

### 🔹 Bronze Layer
- Stores **raw data** as-is from source systems  
- Data is ingested from **CSV files into SQL Server**

### 🔹 Silver Layer
- Performs **data cleaning, standardization, and normalization**
- Prepares data for analysis

### 🔹 Gold Layer
- Contains **business-ready data**
- Modeled using a **Star Schema** for reporting and analytics

---

## 📖 Project Overview

This project includes:

- **Data Architecture**  
  Designing a modern data warehouse using Medallion Architecture  

- **ETL Pipelines**  
  Extracting, transforming, and loading data into the warehouse  

- **Data Modeling**  
  Creating fact and dimension tables optimized for analytics  

- **Analytics & Reporting**  
  Generating SQL-based reports and insights  

---

## 🎯 Skills Demonstrated

This project is ideal for showcasing:

- SQL Development  
- Data Engineering  
- Data Architecture  
- ETL Pipeline Development  
- Data Modeling  
- Data Analytics  

---

## 🛠️ Tools & Resources

All tools used are **free**:

- 📂 **Datasets** – CSV files for ERP & CRM systems  
- 🗄️ **SQL Server Express** – Database hosting  
- 💻 **SQL Server Management Studio (SSMS)** – Database management  
- 🔧 **GitHub** – Version control and collaboration  
- 🧩 **Draw.io** – Architecture and data modeling diagrams  
- 📝 **Notion** – Project planning and templates  

---

## 🚀 Project Requirements

### 🏗️ Data Engineering (Data Warehouse)

#### Objective
Develop a modern data warehouse to consolidate sales data and enable analytical reporting.

#### Specifications
- **Data Sources:** ERP and CRM datasets (CSV files)  
- **Data Quality:** Clean and resolve inconsistencies  
- **Integration:** Combine data into a unified model  
- **Scope:** Use only the latest dataset (no historization)  
- **Documentation:** Provide clear and structured data model documentation  

---

### 📊 Data Analysis (BI & Reporting)

#### Objective
Develop SQL-based analytics to generate insights into:

- Customer Behavior  
- Product Performance  
- Sales Trends  

These insights support **data-driven decision-making**.

📌 For more details, see: `docs/requirements.md`

---
## 📂 Repository Structure

└── requirements.txt # Dependencies

data-warehouse-project/
│
├── datasets/ # Raw datasets used for the project (ERP and CRM data)
│
├── docs/ # Project documentation and architecture details
│ ├── etl.drawio # Shows ETL techniques and methods
│ ├── data_architecture.drawio # Overall project architecture diagram
│ ├── data_catalog.md # Dataset catalog (fields, descriptions, metadata)
│ ├── data_flow.drawio # Data flow diagram
│ ├── data_models.drawio # Data models (Star Schema)
│ ├── naming-conventions.md # Naming standards for tables, columns, files
│
├── scripts/ # SQL scripts for ETL and transformations
│ ├── bronze/ # Raw data extraction and loading
│ ├── silver/ # Data cleaning and transformation
│ ├── gold/ # Analytical models and business-ready data
│
├── tests/ # Testing scripts and data quality checks
│
├── README.md # Project overview and setup instructions
├── LICENSE # License information
├── .gitignore # Ignored files and folders
└── requirements.txt # Project dependencies
---

## ⭐ Key Highlights

- End-to-end **Data Warehouse Development**
- Industry-standard **Medallion Architecture**
- Real-world **ETL pipeline implementation**
- Analytics-ready **Star Schema design**
- Clean and structured **project documentation**

---

## 📌 Conclusion

This project demonstrates how to design and implement a **scalable data warehouse solution**, transforming raw  data into meaningful insights for business decision-making.

