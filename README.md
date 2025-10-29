# Pizza-Sale-Analysis
Analyzed pizza sales data using MySQL Workbench to extract insights on revenue, customer preferences, and order trends. Executed SQL queries to identify top-selling items, calculate revenue metrics, and visualize ordering patterns for data-driven decision-making.

# Project Goal
The primary goal is to perform a detailed data analysis using SQL to answer critical business questions that can drive decision-making for a pizza restaurant.

# Database Schema
The analysis is based on four key relational tables:
- orders → Contains order ID, order date, and order time
- order_details → Includes order detail ID, order ID, pizza ID, and quantity
- pizzas → Contains pizza ID, pizza type ID, size, and price
- pizza_types → Contains pizza type ID, name, category, and ingredients

# Key Analysis & Insights
The SQL queries in this repository are structured to answer the following major business questions, each providing a key insight into the sales performance:
| **Query Objective**                        | **Description / Insight**                                                             |
| ------------------------------------------ | ------------------------------------------------------------------------------------- |
| **1. Total Orders**                        | Counts all unique orders placed in the dataset.                                       |
| **2. Total Revenue**                       | Calculates overall sales revenue generated from all pizza orders.                     |
| **3. Highest-Priced Pizza**                | Identifies the pizza with the maximum unit price.                                     |
| **4. Most Common Pizza Size**              | Determines which pizza size (S, M, L, XL, etc.) is ordered the most.                  |
| **5. Top 5 Most Ordered Pizza Types**      | Lists the five pizzas with the highest total quantities sold.                         |
| **6. Category-Wise Order Quantity**        | Aggregates total pizzas sold by category (Classic, Veggie, Supreme, etc.).            |
| **7. Orders by Hour**                      | Analyzes order frequency by hour to identify peak sales periods.                      |
| **8. Category Distribution**               | Counts the total number of pizzas available per category.                             |
| **9. Average Pizzas per Day**              | Calculates the average number of pizzas ordered daily.                                |
| **10. Top 3 Pizzas by Revenue**            | Finds the top-performing pizzas in terms of revenue contribution.                     |
| **11. Revenue Contribution % by Category** | Calculates each category’s percentage share in total revenue.                         |
| **12. Cumulative Revenue Over Time**       | Tracks revenue growth over time using a window function.                              |
| **13. Top 3 Revenue Pizzas per Category**  | Ranks the top three pizzas by revenue within each category using the RANK() function. |

# Key SQL Concepts Used
- Aggregate Functions → SUM(), COUNT(), AVG(), ROUND()
- Joins → INNER JOIN across multiple related tables
- Grouping and Ordering → GROUP BY, ORDER BY, and aggregate sorting
- Subqueries → Nested queries for average, percentage, and cumulative calculations
- Window Functions → SUM() OVER() and RANK() OVER() for running totals and rankings
- Date and Time Functions → HOUR() extraction to analyze hourly sales trends

# Business Outcomes
- Identified top-selling pizzas and most popular sizes to optimize inventory and marketing.
- Discovered revenue distribution patterns across categories, guiding pricing strategy.
- Highlighted sales peak hours to improve staffing and delivery scheduling.
- Analyzed growth trends and category performance to support data-driven decisions.

