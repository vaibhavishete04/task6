
# Sales Trend Analysis Using SQL

This project performs a sales trend analysis on an e-commerce dataset using MySQL. It was developed as part of a data analyst internship task.

## Objectives

- Calculate monthly revenue and order volume
- Identify top 3 months with highest revenue
- Apply SQL aggregation and date functions

## Table Schema: online_sales

| Column      | Type     | Description           |
|-------------|----------|-----------------------|
| order_date  | DATE     | Date of order         |
| amount      | DECIMAL  | Revenue from order    |
| order_id    | INT      | Unique order ID       |
| product_id  | INT      | Product identifier    |

## SQL Features Used

- GROUP BY with DATE_FORMAT(order_date, '%Y-%m')
- Aggregations: SUM(), COUNT(DISTINCT)
- ORDER BY and LIMIT for ranking

## Sample Outputs

- Monthly revenue trends (e.g., Jan–Apr 2023)
- Top 3 months with highest total sales

## Tech Stack

- MySQL (Online)
- DB-Fiddle (for execution)
