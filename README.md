# SQL Data Warehouse and Analytics Project 🚀
Welcome to the SQL Data Warehouse and ETL Pipeline Project! This project demonstrates the end-to-end development of an SQL-based data warehouse incorporating ETL pipelines and business intelligence (BI) analytics to generate actionable insights. Designed as a portfolio project, it highlights industry best practices in data engineering, data modeling, and analytics.

---

## 🏗️ Data Architecture
The project follows the **Medallion Architecture** with three layers:

![image](https://github.com/user-attachments/assets/baf272bc-46ed-49b7-8ae1-b589cb79e75b)

- **Bronze Layer** – Ingests raw data from source systems (ERP & CRM CSV files).
- **Silver Layer** – Cleanses, transforms, and normalizes data for better quality.
- **Gold Layer** – Stores business-ready data in a star schema for analytics and reporting.

---

## 📖 Project Scope
### ⚙️ Building the Data Warehouse (Data Engineering)
- **Data Sources**: Import structured data from ERP and CRM systems.
- **ETL Pipelines**: Extract, transform, and load data efficiently using SQL & Python.
- **Data Modeling**: Implement fact and dimension tables optimized for analytical queries.
- **Performance Optimization**: Indexing, query tuning, and efficient storage techniques.

### 📊 BI & Analytics (Data Analysis)
Develop **SQL-based** analytics to generate insights on:
- **Customer Behavior**
- **Product Performance Trends**
- **Sales & Revenue Metrics**

These insights empower businesses with data-driven decision-making capabilities.

---

## 🛠️ Tools & Technologies
- 📂 [**Datasets**](https://github.com/Paulette-24/sql-data-warehouse-project/tree/main/datasets) – Access to the project dataset (CSV files).
- 🔗 [**Git Repository**](https://github.com/) - Set up a GitHub account and repository.
- 🛢️ [**SQL Server Express**](https://www.microsoft.com/en-us/sql-server/sql-server-downloads) – Lightweight SQL Server for data warehousing.
- 🖥️ [**SSMS (SQL Server Management Studio**](https://learn.microsoft.com/en-us/ssms/download-sql-server-management-studio-ssms) – GUI for managing databases.
- 🎨 [**Draw.io**](https://www.drawio.com/) – Data architecture and model visualization.
- 📝 [**Notion Project Steps**](https://www.notion.so/SQL-Data-Warehouse-Data-Engineering-Project-1a5373bcdbf8804099f6f43a928eb0da) – Access to all project phases and tasks.

---

## 🗃️ Repository Structure

```sql-data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture details
│   ├── etl.drawio                      # Draw.io file showing different ETL techniques and methods
│   ├── data_architecture.drawio        # Draw.io file showing the project's architecture
│   ├── data_catalog.md                 # Catalog of datasets, including field descriptions and metadata
│   ├── data_flow.drawio                # Draw.io file for the data flow diagram
│   ├── data_models.drawio              # Draw.io file for data models (star schema)
│   ├── naming-conventions.md           # Guidelines for consistent table, column, and file naming
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Scripts for extracting and loading raw data
│   ├── silver/                         # Scripts for cleaning and transforming data
│   ├── gold/                           # Scripts for creating analytical models
│
├── tests/                              # Test scripts and quality assurance files
│
├── README.md                           # Project overview and instructions
├── LICENSE                             # License information for the repository
├── .gitignore                          # Files and directories to be ignored by Git
└── requirements.txt                    # Dependencies and requirements for the project
```

---

## 🎯 Why This Project?

This project is perfect for data engineers, SQL developers, and data analysts looking to showcase expertise in:

✅ **Data Warehousing**  
✅ **ETL Pipeline Development**  
✅ **Dimensional Data Modeling**  
✅ **SQL Query Optimization**  
✅ **Business Intelligence & Analytics**

---

## 🛡️ License

This project is open-source under the **MIT License**. Feel free to use, modify, and contribute!

---

## 🌟 About ME

👩‍💻 Hi there! I'm Paulette, a passionate Data Science Professional who loves transforming raw data into meaningful insights. My goal is to help businesses make data-driven decisions through optimized data solutions.

🚀 **Happy Coding!** 🚀
