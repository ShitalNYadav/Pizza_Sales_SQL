# Pizza Sales Analysis

## Steps Included 
* Understanding the Business Problem.
* Import dataset into the Database.
* Exploring tables present in the Database to identify key insights.
* Analyzing all tables by using given queries.
* Creating Report with all the results and analysis for the company.

## Skills 
* SQL - Used MYSQL Database

## Introduction

Objective : Analyze and manage pizza sales data to gain insights about customer behavior, popular pizzas, order trends, and more.
Tools Used : MySQL for database management and query execution

## Project Overview :       
* This SQL project revolves around a database schema designed to manage and analyse data for a pizza store. The database consists of four primary tables given as following :
Order_details, pizzas, orders and pizza_types
* Each table plays a crucial role in storing different facts of the business operations, from individual orders to the types of pizzas offered. Below is a detailed description of each table and its columns:

## Data Source and Tables 

* Here’s a concise description of each table in the dataset:

**order_details**  
* Stores details about each item (pizza) in an order, such as the specific pizza (pizza_id), the order it belongs to (order_id), and the quantity ordered.
Links to the “orders” table via order_id and to the pizza_types table via pizza_id.

**orders**
* Contains information about customer orders, including the unique order_id, the date (date), and time (time) the order was placed.
Links to the “order_details” table via order_id.

**pizza_types** 
* Describes the types of pizzas available, with a unique pizza_type_id, name, category (e.g., Chicken, Veg), and ingredients.
Links to the “order_details” table via pizza_id (though there may be differences in ID format that need mapping).

**Pizzas**  
* This table has information about pizza size and price of each pizza types 
Links to the “ pizza_types” via pizza_type_id  and with “order_details” via pizza_id

## Entity-Relationship Diagram (ERD):


![image](https://github.com/user-attachments/assets/8b85492e-3854-4ba8-ab44-291fe8ee6e8c)

# SQL Queries:
1. Retrieve the total number of orders placed.
2. Calculate the total revenue generated from pizza sales.
3. Identify the highest-priced pizza.
4. Identify the most common pizza size ordered.
5. List the top 5 most ordered pizza types along with their quantities.
6. Join the necessary tables to find the total quantity of each pizza category ordered.
7. Determine the distribution of orders by hour of the day.
8. Join relevant tables to find the category-wise distribution of pizzas.
9. Group the orders by date and calculate the average number of pizzas ordered per day.
10. Group the orders by date and calculate the average number of pizzas ordered per day.
11. Determine the top 3 most ordered pizza types based on revenue.
12. Calculate the percentage contribution of each pizza type to total revenue.
13. Analyze the cumulative revenue generated over time.
14. Determine the top 3 most ordered pizza types based on revenue for each pizza category.

# Key Insights and Analysis
* Popular Pizza Types: Query results showing the most ordered pizza types.
* Order Trends: Number of orders per day or time of day (e.g., peak order times).
* Quantity Trends: Most commonly ordered quantities for different pizza types.
* Sales by Category: Analysis of which pizza categories (e.g., Chicken, Veg) are most popular.










