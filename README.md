# sales-insights-powerbi-sql
## Project Overview

This project focuses on analysing sales data to generate business insights using SQL and Power BI.  
The complete workflow includes data extraction, data cleaning, ETL, data modelling and dashboard creation.

---

# Tools & Technologies

- MySQL
- SQL
- Power BI
- Power Query (ETL)

---

## 📊 Dataset

Sales transactional data containing:

- customer orders
- product information
- sales amount
- date dimension

---

## 🔁 Project Workflow

1. Data was extracted from MySQL database.
2. Data cleaning and transformations were performed using SQL and Power Query.
3. ETL process was applied inside Power BI.
4. Data modelling was done using relationships between fact and date tables.
5. DAX measures were created for analysis.
6. An interactive dashboard was built for business insights.

---

## 🧹 Data Cleaning & ETL

- Handled missing and inconsistent values
- Converted date columns into proper format
- Removed unnecessary columns
- Created a clean analytical data model inside Power BI

---

## 🗃 SQL Analysis

SQL queries were written to:

- calculate total sales
- analyse yearly sales performance
- validate business metrics before dashboard creation

---

## 📈 Power BI Dashboard

The dashboard provides insights such as:

- Total sales trend by year
- Product-wise sales performance
- Year-wise and product-wise filtering using slicers

Screenshot of the dashboard:

![Dashboard](screenshots/dashboard.png)

---

## 📂 Repository Structure

- `sql/` – SQL queries used for analysis
- `powerbi/` – Power BI report file
- `screenshots/` – dashboard images

---

## 🎯 Key Business Insights

- Sales show clear variation across years
- A small number of products contribute a large portion of total sales
- Year-wise analysis helps identify high and low performing periods

---

## ▶ How to run the project

1. Open the `.pbix` file from the `powerbi` folder in Power BI Desktop.
2. Update database credentials if required.
3. Refresh the data.
