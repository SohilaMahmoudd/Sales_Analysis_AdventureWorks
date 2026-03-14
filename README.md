# Sales Analytics Dashboard – AdventureWorks

## Project Overview
This project presents a **Sales Analysis Dashboard** built using Excel with data sourced from the AdventureWorks database.  
The goal of the project is to transform raw sales data into meaningful insights through data cleaning, modeling, and visualization.

The dashboard provides an interactive way to analyze sales performance, orders, freight costs, and regional distribution.

---

## Data Source
The dataset was extracted from the **AdventureWorks Database**, a Microsoft sample database that contains business data related to sales, products, customers, and territories.

---

## Data Preparation
Data preparation was performed using **Power Query in Excel**. The following steps were applied:

- Removed duplicate records
- Replaced null and missing values
- Removed unnecessary columns
- Standardized data types
- Cleaned and transformed the dataset for analysis

---

## Data Modeling
A **Star Schema** structure was created to organize the data:

### Fact Table
- FactSales

### Dimension Tables
- DimProduct
- DimSubCategory
- DimTerritory
- DimShipMethod
- DimDate

A **Date Dimension** was created to enable time-based analysis such as monthly trends and yearly comparisons.

---

## Data Analysis
Data analysis was performed using **Pivot Tables** in Excel to calculate key metrics including:

- Total Sales
- Total Orders
- Freight Cost Analysis
- Orders by Territory
- Orders by Product Category
- Average Monthly Sales

---

## Dashboard Features
The final dashboard provides several visualizations and KPIs:

### Key Metrics
- Total Sales
- Total Number of Orders

### Visualizations
- Top 10 Products by Freight Cost
- Average Sales per Month
- Orders by Territory
- Orders by Product Category

### Interactive Filters
- Product Color
- SubCategory
- Shipping Method
- Order Date Timeline

These slicers allow users to interactively explore the data.

---

## Tools & Technologies
- Microsoft Excel
- Power Query
- Pivot Tables
- Data Modeling (Star Schema)
- Data Visualization

---

## Project Outcome
This project demonstrates how raw transactional data can be transformed into an **interactive Business Intelligence dashboard** that supports data-driven decision making.
