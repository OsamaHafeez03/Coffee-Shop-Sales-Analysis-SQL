# Coffee Shop Sales Analysis ☕📊
##  📌 Project Overview 
This project involves the analysis of a retail coffee shop's sales dataset to identify key business insights. Using SQL, the project focuses on data cleaning, transformation, and exploratory data analysis (EDA) to calculate Key Performance Indicators (KPIs) such as Total Sales, Month-over-Month (MoM) growth.
## 📂 File Structure
* Coffee Shop Sales.csv: Raw dataset containing transactional records.

* SQl script.sql: SQL script containing queries for database creation, data cleaning, and analytical queries.

* README.md: Project documentation.

## 🛠️ Data Cleaning & Transformation
The SQL script includes strict data preparation steps to ensure accuracy before analysis:

* Database Creation: Creates a dedicated database coffee_shop.


* Column Standardization: Renames the chaotic ï»¿transaction_id column to a clean transaction_id.

Data Type Conversion:


* Date Formatting: Converts transaction_date from a text string (%d/%m/%Y) to a proper SQL DATE format using STR_TO_DATE.


* Time Formatting: Converts transaction_time to a proper SQL TIME format.
