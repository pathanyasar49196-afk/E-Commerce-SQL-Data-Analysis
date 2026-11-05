# E-Commerce SQL Data Analysis

## Project Overview

This project focuses on analyzing E-Commerce sales data using PostgreSQL. It includes 15 SQL analytical queries to examine sales performance, customer purchasing behavior, product performance, revenue trends, and business growth.

The objective is to practice SQL data analysis techniques and extract meaningful business insights from relational datasets.

## Tools and Technologies

- PostgreSQL
- pgAdmin 4
- SQL

## Dataset Description

The project uses five CSV datasets:

| Dataset         | Description                               |
| --------------- | ----------------------------------------- |
| customers.csv   | Customer information and locations        |
| orders.csv      | Customer orders, dates, and order status  |
| order_items.csv | Product quantities, prices, and discounts |
| products.csv    | Product information and categories        |
| payments.csv    | Payment-related information               |

## SQL Concepts Used

- INNER JOIN
- GROUP BY and HAVING
- Aggregate Functions (SUM, COUNT, AVG)
- Common Table Expressions (CTEs)
- Subqueries
- Window Functions
- DENSE_RANK and LAG
- PARTITION BY
- Date Functions
- NULLIF and COALESCE
- Percentage Calculations

## Business Questions Analyzed

1. Calculate total revenue from delivered orders.
2. Count successfully delivered orders.
3. Calculate average order value after discounts.
4. Identify the top 5 revenue-generating products.
5. Analyze total revenue by product category.
6. Calculate monthly sales revenue.
7. Identify the top 10 customers by spending.
8. Analyze sales revenue by city.
9. Calculate average discount percentage by category.
10. Identify products with the highest quantities sold.
11. Find the top 3 revenue-generating products within each category.
12. Calculate monthly revenue growth percentage using LAG.
13. Rank customers based on total spending.
14. Identify and rank customers with more than 5 delivered orders.
15. Calculate each customer's percentage contribution to total revenue.

## Analysis Areas

### Sales Performance

Analysis of delivered orders, total revenue, average order value, and monthly sales trends.

### Product Performance

Identification of top-selling products, revenue-generating categories, and product rankings.

### Customer Analysis

Analysis of customer spending, purchasing frequency, customer rankings, and revenue contributions.

### Revenue Growth

Calculation of month-over-month revenue growth using CTEs and window functions.

## Project Structure

```text
E-Commerce-SQL-Data-Analysis/
|
|-- dataset/
|   |-- customers.csv
|   |-- order_items.csv
|   |-- orders.csv
|   |-- payments.csv
|   |-- products.csv
|   |-- README.md
|
|-- Project 1.sql
|-- README.md
```

## How to Use

1. Download or clone the repository.
2. Create the required tables in PostgreSQL.
3. Import the five CSV datasets into their corresponding tables.
4. Open `Project 1.sql` in pgAdmin.
5. Execute the queries to explore the analysis results.

## Conclusion

This project demonstrates practical SQL skills in relational data analysis, including joins, aggregations, CTEs, subqueries, and window functions. It covers important E-Commerce business metrics such as sales revenue, customer spending, product performance, and monthly revenue growth.

