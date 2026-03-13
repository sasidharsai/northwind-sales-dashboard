
# 📊 Northwind Retail Sales Dashboard (Power BI)

Interactive Power BI dashboard built to analyze retail sales performance using the **Northwind dataset**. The project focuses on identifying revenue trends, product performance, and geographic sales distribution through data modeling and DAX-based metrics.

## 📌 Project Overview

The goal of this project was to design a **clear and interactive business intelligence dashboard** that helps understand how sales and profit are generated across products, categories, customers, and regions.

The dashboard provides a high-level overview of retail performance while also enabling deeper analysis of individual product and category contributions.


## 🏗 Data Model

The dataset was imported from a **SQL file downloaded from Kaggle** and modeled in Power BI using relational table connections.

Tables used in the model:

* **salesorder** – order information and transaction dates
* **orderdetail** – product sales details including quantity, price, and discount
* **product** – product information
* **category** – product category classification
* **customer** – customer details and location

Relationships were created between these tables to enable accurate aggregation of sales and profitability metrics.



## 📊 Key Metrics (DAX)

Several measures were created using DAX to analyze sales performance:

* **Total Sales**
* **Total Profit**
* **Profit Margin (%)**
* **Total Orders**
* **Average Order Value**

These metrics provide insight into both overall business performance and profitability.

## 📈 Dashboard Visuals

![Northwind Dashboard](northwind%20dashboard.png)
The dashboard includes multiple visuals designed to highlight different aspects of sales performance:

* **Monthly Sales Trend** – shows how revenue changes over time
* **Revenue by Country** – identifies geographic sales contribution
* **Category Contribution Treemap** – highlights categories generating the most revenue and profit
* **Top Products by Revenue** – shows best performing products
* **Product Performance Table** – detailed analysis of product sales, quantity, and profitability


## 🛠 Tools & Technologies

* **Power BI** – dashboard development and visualization
* **Power Query** – data cleaning and transformation
* **DAX** – KPI and metric calculations
* **Relational Data Modeling**


## 📁 Dataset Source

The project uses the **Northwind dataset**, downloaded from **Kaggle in SQL format** and imported into Power BI for analysis.


