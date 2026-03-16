# Project Based Internship- Kimia Farma Big Data Analytics
## Project Overview
This project analyzes the sales performance of Kimia Farma from 2020 to 2023 by integrating multiple datasets, including transaction, product, branch, and inventory data. Using Google BigQuery for data processing and Looker Studio for visualization, the project builds an interactive dashboard to explore key business metrics such as total sales, profit, transaction volume, regional performance, and customer ratings.

The goal of this project is to generate actionable insights that help evaluate business performance and support data-driven decision making.

## Business Problem 
Kimia Farma operates many branches across Indonesia and generates large volumes of transactional data. However, the data is stored across multiple datasets, making it difficult to analyze overall business performance.

Without a consolidated dataset, it becomes challenging to evaluate:
1. Overall sales and profit performance
2. Branch-level operational performance
3. Regional sales distribution
4. Customer satisfaction based on transaction ratings

This project aims to integrate these datasets into a unified analytical table to enable efficient analysis and visualization.

## Dataset
The analysis uses four main datasets:

1. Final Transaction
Contains transactional sales data including:
- transaction_id
- date
- branch_id
- product_id
- discount_percentage
- rating_transaksi

2. Product
Contains product information:
- product_id
- product_name
- price

3. Branch Office
Contains branch information:
- branch_id
- branch_name
- kota
- provinsi
- rating_cabang

4. Inventory
Contains product inventory information per branch.

