# 📊 ElectroHub Retail Sales Analytics | End-to-End Power BI & Data Engineering Project

<p align="center">
<img src="Images/dashboard1.png" width="900">
</p>

<p align="center">

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Power Query](https://img.shields.io/badge/Power%20Query-217346?style=for-the-badge)
![DAX](https://img.shields.io/badge/DAX-512BD4?style=for-the-badge)
![Data Engineering](https://img.shields.io/badge/Data-Engineering-blue?style=for-the-badge)

</p>

---

# 🚀 Live Dashboard

### 🔗 Power BI Dashboard

**https://app.powerbi.com/groups/me/reports/xxxxxxxxxxxxxxxxxxxxxxxx?experience=power-bi**

---

# 📖 Project Overview

This project demonstrates an **Enterprise-Level Retail Analytics Solution** built using **Microsoft SQL Server**, **Power BI Desktop**, **Power BI Service**, **Power Query**, and **DAX**.

The objective is to build a scalable Business Intelligence solution capable of ingesting transactional sales data, performing ETL transformations, designing an optimized semantic model, and publishing interactive dashboards to Power BI Service with automated refresh through an **On-Premises Data Gateway**.

The dashboard enables stakeholders to monitor sales performance, profitability, discount effectiveness, customer behavior, product performance, and regional sales trends.

---

# 🎯 Business Problem

Retail businesses generate thousands of transactions every day.

Decision-makers need a centralized reporting system that can answer questions such as:

- Which products generate the highest revenue?
- Which products generate losses?
- Which cities contribute the most sales?
- What is the relationship between Sales and Profit?
- Which promotions perform best?
- How does sales performance change over time?
- Compare two custom date ranges.
- Monitor complete order-level information.

This project solves these challenges using an end-to-end BI architecture.

---

# 🏗️ Solution Architecture

```text
                CSV Dataset
                     │
                     ▼
          Microsoft SQL Server
       (Database & Data Validation)
                     │
                     ▼
             SQL Data Modeling
                     │
                     ▼
            Power BI Desktop
        (Power Query + DAX Model)
                     │
                     ▼
          Interactive Dashboards
                     │
                     ▼
         Publish to Power BI Service
                     │
                     ▼
      On-Premises Data Gateway
                     │
                     ▼
        Scheduled Dataset Refresh
                     │
                     ▼
      Enterprise Business Reporting
```

---

# ⚙️ Technology Stack

| Category | Technology |
|-----------|------------|
| BI Tool | Power BI Desktop |
| Cloud | Power BI Service |
| Database | Microsoft SQL Server |
| ETL | Power Query |
| Query Language | SQL |
| Analytical Language | DAX |
| Data Gateway | On-Premises Gateway |
| Data Source | CSV Files |

---

# 📂 Dataset

The project consists of multiple relational datasets including

- Orders
- Products
- Customers
- Promotions

The data is imported into SQL Server and transformed before visualization.

---

# 🔄 ETL Pipeline

## Phase 1

### Data Ingestion

- Import CSV files into SQL Server
- Create relational database
- Validate imported records

---

## Phase 2

### Data Cleaning

Performed using SQL and Power Query

- Remove duplicate records
- Remove null values
- Change data types
- Rename columns
- Standardize formats
- Data validation

---

## Phase 3

### Data Transformation

- Merge tables
- Build relationships
- Create Calendar Table
- Create Lookup Tables
- Normalize dimensions

---

## Phase 4

### Data Modeling

Implemented

- Star Schema
- One-to-Many Relationships
- Optimized Data Model

---

## Phase 5

### DAX Calculations

Developed business KPIs using DAX.

Examples include

- Total Sales
- Net Sales
- Profit
- Orders
- Quantity Sold
- Discount
- Top Products
- Bottom Products

---

# 📈 Dashboard Features

## Executive Dashboard

✔ Sales by City

✔ Number of Orders

✔ Promotion Performance

✔ Profit vs Net Sales

✔ Sales Trends

---

## Product Performance Dashboard

✔ Top 5 Products by Sales

✔ Bottom 5 Products by Sales

✔ Top 5 Products by Profit

✔ Bottom 5 Products by Profit

✔ Top 5 Products by Quantity Sold

✔ Bottom 5 Products by Quantity Sold

---

## Period Comparison Dashboard

Compare two custom date ranges.

KPIs

- Total Sales
- Total Profit
- Total Quantity Sold

Useful for

- Year-over-Year Analysis
- Quarterly Comparison
- Campaign Comparison

---

## Detailed Sales Report

Interactive report with filters

Available Filters

- Date
- Customer
- Product
- Promotion

Available Metrics

- Order ID
- Customer ID
- Product ID
- Sales
- Profit
- Discount
- Net Sales
- Quantity Sold

---

# 📊 KPIs

- Total Sales
- Net Sales
- Total Profit
- Total Orders
- Quantity Sold
- Discount %
- Promotion Performance
- Sales Trend
- City-wise Sales
- Product Ranking

---

# 📸 Dashboard Preview

## Executive Dashboard

![Dashboard](Images/dashboard1.png)

---

## Product Analytics

![Dashboard](Images/dashboard2.png)

---

## Date Comparison

![Dashboard](Images/dashboard3.png)

---

## KPI Comparison

![Dashboard](Images/dashboard4.png)

---

## Detailed Report

![Dashboard](Images/dashboard5.png)

---

# 🚀 Power BI Service Deployment

This project also demonstrates enterprise deployment.

Workflow

```
SQL Server

↓

Power BI Desktop

↓

Publish

↓

Power BI Workspace

↓

On-Premises Gateway

↓

SQL Connection

↓

Scheduled Refresh

↓

Live Dashboard
```

---

# 💼 Business Insights

- Identify top-performing products
- Detect underperforming products
- Analyze customer buying behavior
- Measure promotion effectiveness
- Monitor city-wise sales performance
- Compare historical periods
- Optimize pricing strategy
- Improve inventory planning

---

# 📁 Repository Structure

```
ElectroHub-Sales-Analytics
│
├── Dashboard
│      └── ElectroHub.pbix
│
├── Dataset
│      ├── Orders.csv
│      ├── Customers.csv
│      ├── Products.csv
│      └── Promotions.csv
│
├── SQL
│      ├── Database.sql
│      ├── Tables.sql
│      └── Queries.sql
│
├── Images
│      ├── dashboard1.png
│      ├── dashboard2.png
│      ├── dashboard3.png
│      ├── dashboard4.png
│      └── dashboard5.png
│
└── README.md
```

---

# ⭐ Key Skills Demonstrated

- Data Engineering
- ETL Pipeline
- SQL Server
- Power Query
- DAX
- Data Modeling
- Star Schema
- Power BI Desktop
- Power BI Service
- Data Gateway
- Business Intelligence
- Dashboard Development
- Data Visualization
- KPI Reporting

---

# 👨‍💻 Author

**Harsh Kumar**

**Aspiring Data Engineer | Data Analyst | Business Intelligence Developer**

- SQL
- Power BI
- DAX
- Power Query
- Microsoft SQL Server
- Python
- Excel
- Data Engineering

---

## ⭐ If you found this project useful, consider giving it a Star.
