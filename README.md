# Python_sales_project
In this project was analyzed and visualized randomly created dataset. 

The generated dataset df simulates transaction data with the following structure:
1.TransactionID: unique identifier for each transaction (ranging from 1 to 2000).
2.Date: Random date for each transaction within the period 2024-01-01 to 2024-06-30.
3.CustomerID: Randomly assigned alphanumeric identifier for customers (40 unique customers).
4.ProductID: Randomly assigned numeric identifier for products (95 unique products).
5.Quantity: Random integer representing the quantity of products purchased in each transaction (between 1 and 99).
6.Price: Random price for each product in the transaction, with two decimals (between 1 and 100).
7.Total amount: Calculated as price multiplied by quantity.

The dataset was analysed by showing the unique number of products and customers, sales per month and week, top 5 products and customers, less sold products and less active customers, average price and quantity. 
Matplotlib, Seaborn and Plotly were used to visualise different aspects of this dataset.
