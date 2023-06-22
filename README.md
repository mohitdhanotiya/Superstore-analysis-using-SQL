# Superstore-analysis-using-SQL
In this Superstore Sales SQL Data Analysis project, an exploratory data analysis was performed on the Superstore Sales Data available on Kaggle. The main aim of the project is to uncover insights into the store's sales and profits trends and patterns. After cleaning and preprocessing the data, the profits trends were visualized by states, region, category, sub-category and timeline (years or quarters). Additionally, top-performing, least-performing products and the most profitable customers were identified.

## Task 1: Understanding the Data  
- This database contains Sales details of transaction of a superstore. 
- The structure has 5 tables, namely 
   - Cust_dimen (containing details about   customer and their respective locations), 
   - Prod_dimen (containing product category and their subcategories), 
   - Orders_dimen (with order no, date, and priority), 
   - Shipping_dimen (with ship date, order and shipping mode), and 
   - market_fact (Orderwise  , marketwise , orderquantity, sales value, discount profit and shipping cost details).

- From this database we can get no of insights from it and it helps in taking various decisions easily. 
- Using  cust_dimen we can get no of customers from various regions which has different customer segments in it.
- Using market_fact we can get which product has highest and lowest sales and then profit according to sales and order quantity.
- Using prod_dimen we can get which products category and product sub category purchased by the customers  using SQL queries.
- Using orders_dimen we can get  products order date and which products has high or low order priority accordingly.
- Using shipping_dimen we can get products shipping date and by which mode the following products shipped.

## Identify and list the Primary Keys and Foreign Keys for   this dataset provided to you.

1. cust_dimen - Cust_id as Primary Key, no foreign key
2. prod_dimen - Prod_id as Primary Key, no foreign key 
3. orders_dimen - Ord_id as Primary Key. But Order_ID will as foreign key in shipping_dimen.
4. shipping_dimen - Shipping id as primary key and Order_ID as foreign key.
5. market_fact - Ord_id, Prod_id, Ship_id and Cust_id as foreign key. No Primary Key
   
