# SQL Supply Chain Analysis

## Overview
This repository contains SQL-based analyses of supply chain data, offering insights such as order trends, customer behavior, item popularity, and cancellations. It’s designed as a learning resource for exploring real-world supply chain challenges.

## Project Files
- **sales_test.csv** — Dataset containing order-level information: `ORDER_NO`, `CUSTOMER_NO`, `ITEM`, `NS_ORDER` (number ordered), `NS_SHIP` (number shipped), and `DATE`.
- **canceled_test.csv** — Dataset tracking cancellations: `CUSTOMER_NO`, `ITEM`, `NC_ORDER` (number of items canceled), `NC_SHIP` (number of canceled items shipped).
- **Supply Chain Query.sql** — Contains categorized SQL queries to explore and analyze the datasets.

## Analytics & Query Categories

###  Easy
1. Count of orders placed in January 2017  
2. Total units ordered in February 2017  
3. Canceled orders per customer  
4. Number of unique customers  
5. Average items ordered per order  
6. Top-ordered items  
7. Successful orders by specific customers  

### Intermediate
8. Units ordered vs. canceled for overlapping items  
9. Detailed canceled vs. successful order comparisons  
10. Order classification by volume (High / Medium / Low)  
11. Shipped items as a percentage of ordered items per customer  
12. Top 3 customers by canceled orders  
13. Items where cancellations exceed shipments  
14. Customer with highest orders in January 2017  

### Advanced
15. Cumulative ordered units per customer over time  
16. Customers with the most cancellations and their total sales  
17. Contribution percentage of top 5 customers to total sales  
18. ABC classification of items by sales contribution  

These queries help uncover trends like cancellation rates, top-performing items/customers, and inventory prioritization via ABC analysis (commonly used in inventory management to categorize items by importance) :contentReference[oaicite:0]{index=0}.

## Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/rajatsharma63/SQL-Supply-Chain-Analysis.git
   
2. Import the CSV files (sales_test.csv, canceled_test.csv) into your SQL environment (e.g., MySQL, PostgreSQL).

3. Run the queries in Supply Chain Query.sql to explore the data and generate insights.

4. Customize queries or add new analyses as needed for your use case.





## Purpose & Key Learnings

- 🛠️ Hands-on application of SQL for analyzing supply chain data.  
- 📦 Learn how to handle datasets involving orders and cancellations.  
- 📊 Understand customer behavior, cancellation patterns, and item prioritization (via ABC analysis).  
- 🎯 Gain valuable insights for real-world decision-making in supply chain management.
