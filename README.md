# SQL-Analysis-Ecommerce
This repository contains SQL queries and analysis scripts for a comprehensive business analysis of Olist, a Brazilian e-commerce platform.

The goal of this project is to extract meaningful insights regarding product performance, profitability, sales distribution, and customer satisfaction that can aid in making informed business decisions.

Datasets
The analysis is based on multiple datasets that are part of the larger "Brazilian E-Commerce Public Dataset by Olist" available on Kaggle (https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce/data). These datasets include:

OLIST_CUSTOMERS_DATASET
OLIST_GEOLOCATION_DATASET
OLIST_ORDER_ITEMS_DATASET
OLIST_ORDER_PAYMENTS_DATASET
OLIST_ORDER_REVIEWS_DATASET
OLIST_PRODUCTS_DATASET
OLIST_SELLERS_DATASET
PRODUCT_CATEGORY_NAME_TRANSLATION

Each dataset comprises various fields that detail the transactions, products, and user interactions on the Olist platform.

SQL Analysis
The SQL queries developed as part of this analysis serve the following purposes:

Joining various datasets to create a holistic view of the order process.
Calculating the total order value and average review scores to gauge customer satisfaction and product performance.
Analyzing geographic sales distribution to understand market penetration and potential areas for expansion.
Queries
Join Operations: Created SQL JOIN operations to link related data from different datasets, enabling a unified view of the business data.

The query for joining order_items with products, orders, customers, and sellers datasets is provided.
Product Performance: Developed queries to assess the performance of products based on sales volume, value, and customer reviews.

Example of calculated fields: Total sales per product, average rating, total sales value.
Geographic Distribution: Constructed queries to analyze the sales distribution across different geographic locations.

Example output: Number of orders per state, sales value per region.
How to Run the SQL Scripts
Download the datasets from the Kaggle link provided above.
Set up your SQL environment (e.g., PostgreSQL, MySQL).
Import the datasets into your database management system.
Run the provided SQL scripts in your SQL environment to replicate the analysis.
Results
The results of the SQL queries are presented in this repository as CSV files and screenshots to showcase the expected outputs of each analysis step.

Tools Used
SQL Database (Oracle MySQL)
Any other tools used for visualization or additional data processing.
