# Pizza Sales Analysis

## Steps Included 
* Understanding the Business Problem
* Import dataset into the Database 
* Exploring tables present in the Database to identify key variables
* Analyzing the key variables
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

* order_details  
  **Stores details about each item (pizza) in an order, such as the specific pizza (pizza_id), the order it belongs to (order_id), and the quantity ordered.
Links to the “orders” table via order_id and to the pizza_types table via pizza_id.**

* orders 
**Contains information about customer orders, including the unique order_id, the date (date), and time (time) the order was placed.
Links to the “order_details” table via order_id.**

* pizza_types 
**Describes the types of pizzas available, with a unique pizza_type_id, name, category (e.g., Chicken, Veg), and ingredients.
Links to the “order_details” table via pizza_id (though there may be differences in ID format that need mapping).**

* Pizzas  
**This table has information about pizza size and price of each pizza types 
Links to the “ pizza_types” via pizza_type_id  and with “order_details” via pizza_id**





