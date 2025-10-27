# 📊 AdventureWorks Sales Dashboard (SQL + Power BI)

## 🧩 Overview
This project demonstrates the complete process of data cleaning, transformation, and visualization using **SQL** and **Power BI**.  
The goal is to extract meaningful business insights from the **AdventureWorks** dataset and present them in a dynamic, interactive dashboard.

---

## 🚀 Project Workflow

### 1. Data Preparation (SQL)
- Restored the **AdventureWorksDW2019** database in Microsoft SQL Server Management Studio (SSMS).  
- Cleaned and transformed raw tables using SQL queries.  
- Exported the cleaned data into CSV files for Power BI visualization.

### 2. Data Modeling (Power BI)
- Imported cleaned CSVs and Excel files into Power BI.  
- Created relationships between tables in the **Model View**.  
- Further processed data using **Power Query** (renaming columns, setting data types, etc.).

### 3. Dashboard Creation (Power BI)
- Designed an interactive dashboard with key metrics and visuals.  
- Pages include:
  - **Sales Overview**
  - **Sales by Customer**
  - **Sales by Product**

---

## ⚙️ How to Run the Project
1. **Open** the `.pbix` file in **Power BI Desktop**.  
2. **Connect** to your SQL Server instance containing the **AdventureWorks** database.  
3. **Refresh** the data to load the latest metrics and visualizations.

---

## 📁 Project Files
- `AdventureWorks_Sales_Dashboard.pbix` — Power BI project file  
- `adventureworks_queries.sql` — SQL cleaning and transformation script  
- CSV files — Exported cleaned data for visualization  
- `dashboard_report.pdf` — Static report version (optional)

---

## 🌱 Future Scope
In the next phase, the project will be automated using **Python**.  
The process will:
- Pull data automatically from the database  
- Clean and organize it using **Pandas/Numpy**  
- Generate Power BI visuals  
- Export the dashboard as a PDF  
- Email it automatically to stakeholders

---

## 📚 Dataset Source
- [Microsoft SQL Server Samples - AdventureWorksDW2019](https://github.com/microsoft/sql-server-samples/releases/download/adventureworks/AdventureWorksDW2019.bak)

---

## 💡 Goal
To demonstrate strong analytical, technical, and visualization skills by integrating SQL-based data cleaning with Power BI dashboarding — a step toward building end-to-end data engineering and analytics workflows.
