# sql_retail_sales

# Project Overview

This project is a beginner-level SQL data analysis project built using SQL Server.

The goal of this project is to:

Create a retail sales database
Perform data cleaning
Explore the dataset
Answer business-related questions using SQL queries
Practice aggregation, filtering, grouping, and window functions

This project is ideal for freshers and beginners who want to strengthen their SQL fundamentals.


# Database Created

CREATE DATABASE sqlProject1;


# Data Cleaning
The following checks were performed:
Checked for NULL values in important columns
Removed records where key fields were NULL
Verified total number of records
Checked unique customers
Explored available categories
This step ensures the dataset is clean and reliable for analysis.

##  Business Questions Solved
# Q1 – Sales on Specific Date

Retrieve all sales made on '2022-11-05'.

# Q2 – Clothing Sales (Nov 2022, Quantity > 4)

Find transactions in the Clothing category where:

Month = November 2022
Quantity ≥ 4
# Q3 – Total Sales per Category

Calculate:

Total revenue per category
Total number of orders per category
# Q4 – Average Age (Beauty Category)

Find the average age of customers purchasing from Beauty category.

# Q5 – High Value Transactions

Find transactions where total_sale > 1000.

# Q6 – Transactions by Gender per Category

Count total transactions grouped by:

Category
Gender
# Q7 – Best Selling Month Per Year

Calculate:

Average monthly sales
Rank months within each year
Identify best-performing month


# Q8 – Top 5 Customers

Find top 5 customers based on highest total spending.

# Q9 – Unique Customers per Category

Count distinct customers in each category.

# Q10 – Sales by Shift

Classify sales into:

Morning (< 12)
Afternoon (12–17)
Evening (> 17)

Count total orders per shift using a CTE.
