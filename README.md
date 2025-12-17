# Coffee Shop Sales Analysis ☕📊
##  📌 Project Overview 
This project involves the analysis of a retail coffee shop's sales dataset to identify key business insights. Using SQL, the project focuses on data cleaning, transformation, and exploratory data analysis (EDA) to calculate Key Performance Indicators (KPIs) such as Total Sales, Month-over-Month (MoM) growth.
## 📂 File Structure
* Coffee Shop Sales.csv: Raw dataset containing transactional records.

* SQl script.sql: SQL script containing queries for database creation, data cleaning, and analytical queries.

* README.md: Project documentation.

## 🛠️ Data Cleaning & Transformation
The SQL script includes strict data preparation steps to ensure accuracy before analysis:

1. Database Creation: Creates a dedicated database coffee_shop.


2. Column Standardization: Renames the chaotic ï»¿transaction_id column to a clean transaction_id.

3. Data Type Conversion:


* Date Formatting: Converts transaction_date from a text string (%d/%m/%Y) to a proper SQL DATE format using STR_TO_DATE.


* Time Formatting: Converts transaction_time to a proper SQL TIME format.

## 📈 Key Performance Indicators (KPIs)
The SQL analysis focuses on the following dynamic metrics, specifically filtered for May 2023 as the reference month:
1. Total Sales Analysis
* Metric: Total Revenue (SUM(unit_price * transaction_qty))

* MoM Growth: Calculates the percentage increase/decrease in sales compared to the previous month (April).

  * Formula: ((May Sales - April Sales) / April Sales) * 100
2. Total Orders Analysis
* Metric: Total number of transactions.

* MoM Growth: Tracks the volume of customer visits month-over-month.
3. Total Quantity Sold
* Metric: Total units of products sold.

* MoM Growth: Analyzes if customers are buying more items per visit.

## 🔍 Analytical Insights
Based on the SQL analysis of this dataset, the following trends were identified:

* Sales Growth: The business shows a strong upward trend in revenue from January through June. May specifically generated approximately $157k in revenue.

* Peak Hours: The busiest sales hours are consistently between 8:00 AM and 10:00 AM, aligning with the morning commute rush.

* Top Products: Barista Espresso, Latte, and Hot Chocolate are among the highest revenue-generating items.

* Best Performing Store: Hell's Kitchen typically outperforms the other two locations in both transaction volume and total revenue.

* Weekly Trends: Fridays are often the busiest days of the week, while Sundays see the lowest foot traffic.
