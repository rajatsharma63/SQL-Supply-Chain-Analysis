# SQL Supply Chain Analysis

## Project Overview

This project uses SQL to analyze supply chain data, focusing on orders, cancellations, and customer trends. It includes datasets and queries to help understand how SQL can be applied to real-world supply chain problems. This project demonstrates a comprehensive analysis of supply chain data using SQL. It covers a range of insights such as order trends, customer behavior, item popularity, and advanced classifications. The dataset includes sales data (`sales_test.csv`) and cancellations data (`canceled_test.csv`). The queries are categorized into Easy, Intermediate, and Advanced levels based on complexity.

## Features

* **Basic Analytics**: Total orders, unique customers, and average items ordered.
* **Customer Insights**: Top customers, canceled orders, and successful order rates.
* **Item Trends**: Top-ordered items, ABC classification, and canceled vs. shipped items.
* **Advanced Techniques**: Cumulative sales, order rankings, and customer contributions to sales.

## Tools and Technologies

* **Database**: MySQL
* **Programming Language**: SQL
* **Dataset**: `sales_test.csv` and `canceled_test.csv`

## Dataset

The dataset for this project is composed of two CSV files:

### `sales_test.csv`

Contains details about orders placed, including:

* `ORDER_NO`: Order ID
* `CUSTOMER_NO`: Customer ID
* `ITEM`: Item ordered
* `NS_ORDER`: Number of items ordered
* `NS_SHIP`: Number of items shipped
* `DATE`: Date of the order

### `canceled_test.csv`

Contains information on cancellations, including:

* `CUSTOMER_NO`: Customer ID
* `ITEM`: Item canceled
* `NC_ORDER`: Number of items canceled
* `NC_SHIP`: Number of canceled items shipped

## SQL Queries

The SQL queries for this analysis are categorized by difficulty:

### Easy Level

* Total number of orders.
* Total number of unique customers.
* Average items ordered per order.
* Top 5 most ordered items.
* Total successful orders for specific customers.

### Intermediate Level

* Comparison of ordered vs. canceled units for items appearing in both datasets.
* A detailed comparison between canceled and successful orders for the same items.
* Classification of orders as 'High', 'Medium', or 'Low' based on volume.
* Calculation of shipped items as a percentage of ordered items for each customer.
* Identification of the top 3 customers with the highest number of canceled orders.
* Listing items that were canceled more often than they were shipped.
* Finding the top-ordering customer in January 2017.

### Advanced Level

* ABC classification of items into A, B, and C categories based on their contribution to sales.

## How to Use

1.  Load the datasets (`sales_test.csv` and `canceled_test.csv`) into your SQL database.
2.  Execute the provided SQL queries in your SQL environment.
3.  Review the results and insights generated.
