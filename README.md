# COFFEE SHOP SALES ANALYSIS
![](image_of_coffee_shop.png)![](image_of_coffee_shop.png)
## project overview 
Objective: The objective of this project is to analyze the sales transactions of a coffee shop located in Lower Manhattan. The goal is to gain insights into sales performance, identify the most popular products, understand revenue distribution across different categories, and determine peak sales hours. This analysis will help in making data-driven decisions to optimize inventory, enhance marketing strategies, and improve overall business operations
---
## data source/data set description 
The dataset consists of sales transactions from a coffee shop located in Lower Manhattan. The data was collected on January 1, 2023, the that was provided in an excel format and includes the following columns:
- transaction_id: A unique identifier for each transaction.
-	transaction_date: The date of the transaction.
-	transaction_time: The time the transaction occurred.
-	transaction_qty: The quantity of items purchased in the transaction.
-	store_id: The identifier for the store where the transaction took place.
-	store_location: The location of the store (Lower Manhattan).
-	product_id: The identifier for the product sold.
-	unit_price: The price per unit of the product.
-	product_category: The category to which the product belongs (e.g., Coffee, Tea, Drinking Chocolate, Bakery).
-	product_type: The type of product sold (e.g., Gourmet brewed coffee, Brewed Chai tea, Hot chocolate, Scone).
-	product_detail: Specific details about the product (e.g., Ethiopia Rg, Spicy Eye Opener Chai Lg, Dark chocolate Lg).
-	REVENUE: The total revenue generated from the transaction.
-	Month_name: The name of the month in which the transaction occurred.
-	month: The numerical representation of the month (1 for January).
-	weekday: The numerical representation of the day of the week (7 for Sunday).
-	Weekday_name: The name of the day of the week (Sunday).
-	hour: The hour at which the transaction occurred.
  ---
  ## TOOLS 
  - Microsoft Excel
     1. data cleaning
     2. data transformation
     3. data analysis
     4. dashboard
## problem Statement 
- Trend Analysis: How do sales trends vary by time of day, day of the week, or month?
- Sales Volume: What are the peak hours for sales in different store locations?
- Product Performance: Which products are the top performers in terms of sales volume and revenue?
- Purchase Patterns: What are the most common product combinations purchased together?
- Customer Segmentation: How can customers be segmented based on their purchasing behavior?  Store Performance:
- Store Comparison: How do different store locations compare in terms of sales volume and revenue?
- Performance Metrics: What are the key performance metrics for each store location?
---
## skills deployed
Data cleaning and transformation 
1. sorted and fliltered the data to remove duplicate values 
2. added the revenue column by multiplying the quantity sold and unit cost using the syntax (=H2*D2)
3. added the month-name columns by using the syntax  (=TEXT(B2,"mmm")
4. added the weekday column by using the syntax (=TEXT(B2, "dddd")
5. added the hour of the day column by using the syntax (=HOUR(C2)
# ANALYSIS 
1. Total transaction by Product Category
  - Objective: Determine the revenue contribution of each product category.
  - Pivot Table Setup:
    . Rows: product_category
    . Values: count of transaction
2. Total Revenue by Product Type
 - Objective: Identify which product types generate the most revenue.
 - 	Pivot Table Setup:
	. Rows: product_type
	. Values: Sum of REVENUE


