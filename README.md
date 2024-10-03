# Comprehensive SQL Query Analysis for Pizza Orders
## Project Overview
This project analyzes a pizza order dataset using SQL to answer critical business questions. The goal was to retrieve insights on order volume, revenue, popular pizza types, and other sales trends by writing optimized SQL queries. This project demonstrates the ability to solve real-world business problems through data extraction and analysis.

## Problem Statements
Basic Queries:

1. Retrieve the total number of orders placed.
2. Calculate the total revenue generated from pizza sales.
3. Identify the highest-priced pizza.
4. Identify the most common pizza size ordered.
5. List the top 5 most ordered pizza types along with their quantities.

Intermediate Queries:

6. Find the total quantity of each pizza category ordered.
7. Determine the distribution of orders by hour of the day.
8. Find the category-wise distribution of pizzas.
9. Group the orders by date and calculate the average number of pizzas ordered per day.
10. Determine the top 3 most ordered pizza types based on revenue.

Advanced Queries:
11. Calculate the percentage contribution of each pizza type to total revenue.

## Queries:
1. Retrieve the total number of orders placed.

      ```SELECT COUNT(order_id) FROM orders```
   
