# SQL project on Pizza Sales

This project focuses on analyzing pizza sales data using SQL to extract meaningful business insights.
The analysis covers basic, intermediate, and advanced SQL queries to understand revenue patterns, customer ordering behavior, and product performance.

The objective of this project is to demonstrate strong SQL skills including database creation, joins, aggregations, grouping, and advanced analytical queries.



## Dataset Description

### The project uses four relational datasets:<br>
##### 1️.orders.csv<br>
Contains order-level information<br>
Columns: order_id, order_date, order_time<br>
Used to analyze total orders and time-based trends<br><br>

##### 2️.order_details.csv<br>
Contains item-level details for each order<br>
Columns: order_details_id, order_id, pizza_id, quantity<br>
Used to calculate total pizzas sold and link orders with products<br><br>

##### 3️.pizzas.csv<br>
Contains pizza size and pricing information<br>
Columns: pizza_id, pizza_type_id, size, price<br>
Used for revenue calculations and size-based analysis<br><br>

##### 4️. pizza_types.csv<br>
Contains pizza category and ingredient details<br>
Columns: pizza_type_id, name, category, ingredients<br>
Used for category-level and type-level analysis<br><br>
