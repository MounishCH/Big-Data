# Web App for Product Recommendation based on Market Basket Analysis and Customer Segmentation using RFM Analysis

## Overview
Data science and machine learning are very much applicable in such huge and various fields. One of them is retail business. Imagine if you are a retail business owner who owns a retail shop that sells hundreds of items. In a single month, there are more than a hundred transactions occurring in your shop, for instance. Each transaction is usually made with more than an item to be bought. It means there are usually more than an item in a single transaction.

Market Basket Analysis is one of the key techniques used by large retailers to uncover associations between items. It works by looking for combinations of items that occur together frequently in transactions. To put it another way, it allows retailers to identify relationships between the items that people buy. Association Rules are widely used to analyze retail basket or transaction data, and are intended to identify strong rules discovered in transaction data using measures of interestingness, based on the concept of strong rules.

**Codelabs Report Link:** https://codelabs-preview.appspot.com/?file_id=1VQ5vytQq5Jt9ZrE-Gy3NCV3zN8MX0Pq5mishS0GTDDo#0

## Usage Guide
- To run the application run the following command on terminal:
```
streamlit run streamlitapp.py
```
- Feature Engineering, EDA, Market Basket Analysis and Customer Segmentation notebooks can be under `/notebooks` folder.

## Goals
Goal is to create an interface with an interactive dashboard, along with recommendations for products based on market basket analysis and customer segments identified in the historical dataset. The app will allow analyzing the data on a more granular level, such as understanding the purchasing pattern specific to a country
- Identifying target customer segments to build promotional strategies 
- Provide an interactive dashboard to analyze country level performance of products, customers and sales revenue statistics on a monthly, weekly, and daily level
- Perform Market Basket Analysis to develop more effective product placement, pricing, cross-sell, and up-sell strategies on retail dataset
- Recommend products based on association rules generated using Apriori Algorithm for similar customers

## Use cases
- The main objective of market basket analysis is to identify products that customers may want to purchase
- Market basket analysis enables sales and marketing teams to develop more effective product placement, pricing, cross-sell, and up-sell strategies

## About the data
- [Online Retail Dataset](https://archive.ics.uci.edu/ml/machine-learning-databases/00352/Online%20Retail.xlsx)
- It is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.
- Features:
  - InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
  - **StockCode**: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product. 
  - **Description**: Product (item) name.
  - **Quantity**: The quantities of each product (item) per transaction.
  - **InvoiceDate**: Invoice date and time. Numeric, the day and time when each transaction was generated. 
  - **UnitPrice**: Unit price. Numeric, Product price per unit in sterling.
  - **CustomerID**: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer. 
  - **Country**: Country name. Nominal, the name of the country where each customer 
