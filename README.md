📊 Northwind Retail Sales Performance Dashboard (Power BI)

Interactive retail analytics dashboard built using Power BI, designed to analyze sales performance, profitability, and product contribution using the Northwind dataset.

📌 Project Overview

This project focuses on analyzing retail sales data to understand revenue trends, product performance, and geographic sales distribution.
The dashboard provides a high-level business view while allowing deeper analysis of product profitability and sales behavior.

The objective was to design a clean, executive-style dashboard that helps decision-makers quickly identify revenue drivers and performance patterns.

🏗 Data Modeling

The dataset was modeled using a relational structure similar to a star schema to ensure efficient analysis and scalable reporting.

Tables used:

salesorder → order information and transaction dates

orderdetail → product sales details (quantity, price, discount)

product → product information

category → product category classification

customer → customer details and location

Relationships

salesorder → orderdetail

product → orderdetail

category → product

customer → salesorder

This structure enables efficient aggregation of metrics such as sales, profit, and order volume across different business dimensions.

📊 Key Metrics Created (DAX)

Several analytical measures were created using DAX to support business insights.

Core KPIs

Total Sales

Total Profit

Profit Margin %

Total Orders

Average Order Value

Additional Metrics

Total Quantity Sold

Sales per Product

Sales per Customer

Monthly Sales Trend

These KPIs provide insight into revenue performance, profitability, and customer behavior.

📈 Dashboard Highlights

The Power BI dashboard includes multiple interactive visuals designed to answer different business questions.

Key visuals include:

Monthly Sales Trend – analyzes how revenue evolves over time

Revenue by Country – identifies geographic sales contribution

Category Contribution Treemap – shows which product categories drive revenue and profit

Top Products by Revenue – highlights best-selling products

Product Performance Table – detailed product-level analysis including sales, profit, and margin

Users can explore sales performance through interactive filtering and dynamic visuals.

📌 Key Business Insights

Analysis of the dataset reveals several interesting business observations:

Certain countries contribute significantly more to total revenue than others

Some products generate high sales volume but lower profit margins

A small number of products account for a large share of total revenue

Category performance varies significantly when comparing revenue and profitability

These insights help identify which products and regions drive business performance.

🛠 Tools & Technologies

Power BI – dashboard development and visualization

Power Query – data transformation

DAX – KPI and metric calculations

Relational Data Modeling

📁 Dataset Source

The dataset used in this project is the Northwind retail dataset, downloaded from Kaggle in SQL format.

The SQL file was imported into a relational database and then connected to Power BI for analysis. The dataset contains multiple related tables representing customers, products, categories, and sales transactions.
