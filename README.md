# Zepto-SQL-Project
This project involves an end-to-end data analysis of a Zepto retail dataset using PostgreSQL. The primary goal was to transform raw data into actionable business insights, focusing on data cleaning, inventory categorization, and revenue forecasting.
📁 Repository Structure
zepto-SQL-project.sql: The main script containing table schemas, data cleaning procedures, and analytical queries.
zepto_revenue_report(in).csv: Exported query results showing the calculated revenue and category-wise insights
🛠️ Key Analysis & Features
Data Cleaning & Standardization:
Removed inconsistent records (e.g., products with zero MRP).
Normalized pricing by converting values from Paisa to Rupees.

Inventory Categorization:
Used conditional logic to classify products into Low, Medium, and Bulk segments based on weight.
Business Intelligence Queries:
Revenue Estimation: Calculated potential revenue per category based on available quantity and discounted prices.
Discount Analysis: Identified top-performing categories based on average discount percentages.
Value Analysis: Calculated 'Price per Gram' to identify the best-value products for customers.
Stock Monitoring: Analyzed the ratio of In-Stock vs. Out-of-Stock items.

🚀 SQL Techniques Utilized
Data Manipulation (DML): INSERT, UPDATE, DELETE.
Aggregate Functions: SUM(), AVG(), COUNT(), ROUND().
Conditional Expressions: CASE WHEN statements for dynamic grouping.
Advanced Filtering: GROUP BY, HAVING, DISTINCT, and ORDER BY.

Tools Used: PostgreSQL, pgAdmin 4
