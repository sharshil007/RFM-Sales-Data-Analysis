# RFM-Sales-Data-Analysis

Introduction: 
The Sales Data Analysis project is a comprehensive exploration of sales data from a database. This project aims to extract meaningful insights and valuable information from a large dataset related to sales transactions. By leveraging SQL queries and data analysis techniques, the project delves into various aspects of the data, including product performance, customer behavior, and sales trends.

Key Objectives:

Data Inspection: The project begins by inspecting the raw data, exploring its structure, and identifying unique values in critical columns such as product lines, countries, and sales statuses.
Sales Analysis: It performs in-depth sales analysis, including aggregating sales figures by product line, year, and deal size, allowing stakeholders to identify top-performing product lines and monitor sales trends over time.
Customer Segmentation: The project implements RFM (Recency, Frequency, Monetary Value) analysis to segment customers based on their transaction history, helping businesses understand their customer base better.
Product Association: Using SQL queries, the project uncovers which products are frequently sold together, providing valuable insights for marketing and inventory management.
Geographic Analysis: It also analyzes sales data geographically, determining the highest revenue-generating cities within specific countries.

This script includes various SQL queries for data inspection and analysis. Below is a summary of the different sections and their purposes:

Analysis:

Grouping Sales by Product Line: Summarizes sales data by PRODUCTLINE and sorts by revenue in descending order.
Grouping Sales by Year: Summarizes sales data by YEAR_ID and sorts by revenue in descending order.
Grouping Sales by Deal Size: Summarizes sales data by DEALSIZE and sorts by revenue in descending order.
Best Month for Sales in a Specific Year: Determines the best month for sales in a specific year (YEAR_ID) and calculates the revenue and frequency of orders for each month.
Best Product Line in the Best Sales Month: Identifies the product line that was sold the most in the best sales month (November in this case).

Customer Analysis:
Calculates RFM (Recency, Frequency, Monetary Value) metrics for each customer.
Segments customers based on RFM scores into categories such as "lost customers," "slipping away," "new customers," "potential churners," "active," and "loyal."

Product Association:
Analyzes which products are often sold together by identifying orders with the same ORDERNUMBER.
Lists the product codes that are frequently sold together.

Extras:
Identifies the city with the highest sales revenue in a specific country (e.g., 'UK' in this case).
Determines the best-selling product line in the United States ('USA') by year.


Benefits:
This Sales Data Analysis project equips businesses with actionable insights to make informed decisions. By understanding their sales patterns, customer behavior, and product associations, organizations can optimize marketing strategies, inventory management, and customer relationships.
