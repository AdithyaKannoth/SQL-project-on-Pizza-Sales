# SQL project on Pizza Sales

This project focuses on analyzing pizza sales data using SQL to extract meaningful business insights.
The analysis covers basic, intermediate, and advanced SQL queries to understand revenue patterns, customer ordering behavior, and product performance.

The objective of this project is to demonstrate strong SQL skills including database creation, joins, aggregations, grouping, and advanced analytical queries.



## Dataset Description
The dataset used in this project is publicly available and commonly used for SQL practice and data analysis projects.
Dataset Name: Pizza Sales Dataset
Source: Kaggle<br>

### The project uses four relational datasets:<br>
##### 1️.orders.csv<br>
Contains order level information<br>
Columns: order_id, order_date, order_time<br>
<br>

##### 2️.order_details.csv<br>
Contains item level details for each order<br>
Columns: order_details_id, order_id, pizza_id, quantity<br>


##### 3️.pizzas.csv<br>
Contains pizza size and pricing information<br>
Columns: pizza_id, pizza_type_id, size, price<br>
<br>

##### 4️. pizza_types.csv<br>
Contains pizza category and ingredient details<br>
Columns: pizza_type_id, name, category, ingredients<br>
<br>


### Analysis Performed:
##### Basic Analysis
Total number of orders placed<br>
Total revenue generated<br>
Highest priced pizza<br>
Most common pizza size ordered<br>
Top 5 most ordered pizza types

##### Intermediate Analysis
Total quantity ordered per pizza category<br>
Distribution of orders by hour<br>
Category wise pizza distribution<br>
Average pizzas ordered per day<br>
Top 3 pizzas based on revenue

##### Advanced Analysis
Percentage revenue contribution of each pizza type<br>
Cumulative revenue over time<br>
Top 3 revenue generating pizzas per category

### Key Insights

Identified peak order hours and daily trends<br>
Determined most popular pizza sizes and categories<br>
Analyzed revenue contribution of different pizza types<br>
Extracted top performing products based on revenue<br>
