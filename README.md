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
[Download Dataset](https://drive.google.com/drive/folders/1DNBK01xV5ymcsyghBO2VBII7bxacGtt0?usp=sharing)
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

## Dashboard
[Full Dashboard](https://lookerstudio.google.com/reporting/2975706f-dccd-4a65-bedb-45ad64e08a43)
An interactive dashboard was created in Looker Studio to visualize business performance.
The dashboard includes:
- Total Sales
- Total Profit
- Total Transactions
- Average Transaction Rating
- Revenue Trends (2020–2023)
- Top Provinces by Transactions
- Top Provinces by Net Sales
- Branch Rating vs Transaction Rating Analysis
- Profit Distribution by Province

## Key Insights

- Kimia Farma generated approximately Rp346.96B in sales and Rp98.54B in profit from 672K transactions between 2020 and 2023.
- Sales and transaction volumes are concentrated in Jawa Barat, Jawa Tengah, Jawa Timur, and Sumatera Utara.
- Revenue trends show relatively stable performance across the analyzed years.
- Several branches show high branch ratings but lower transaction ratings, indicating potential issues in transaction service quality.
- Profit contribution varies significantly across provinces, highlighting opportunities for regional optimization.

## Business Recommendation 
1. Improve Transaction Experience
Branches with high branch ratings but lower transaction ratings should improve:
- service efficiency
- cashier workflow
- queue management

2. Expand in High Performing Regions
Regions such as Jawa Barat and Jawa Timur show strong demand and could benefit from:
- additional branches
- expanded healthcare services
- increased marketing investment

3. Strengthen Sales in Low Performing Regions
To improve performance in lower sales regions:
- implement targeted marketing campaigns
- introduce promotional programs
- collaborate with local healthcare providers

4. Optimize Product Strategy
Profitability can be improved by:
- promoting higher-margin products
- introducing product bundles
- optimizing pricing strategies
