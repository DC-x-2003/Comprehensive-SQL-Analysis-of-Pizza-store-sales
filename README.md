# Comprehensive-SQL-Analysis-of-Pizza-store-sales
A comprehensive analysis of pizza sales data using SQL, uncovering key insights into sales trends, popular pizzas, and customer preferences. This project utilises four datasets to provide a detailed look at the restaurant's performance and operational efficiency.

## Project Overview

This project involves a comprehensive analysis of pizza sales data using SQL. The objective is to uncover key trends and insights by solving a range of queries from basic to complex. The project is divided into four main datasets: Pizzas, Pizza Types, Orders, and Order Details.

## Datasets

1. Pizzas Dataset
+ pizza_id: Unique identifier for each pizza.
+ pizza_type_id: Identifier linking the pizza to its type.
+ size: Size of the pizza (e.g., Small, Medium, Large).
+ price: Price of the pizza.

2. Pizza Types Dataset 
+ pizza_type_id: Unique identifier for each pizza type.
+ name: Name of the pizza type.
+ category: Category of the pizza (e.g., Vegetarian, Non-Vegetarian).
+ ingredients: Ingredients used in the pizza.

3. Orders Dataset
+ order_id: Unique identifier for each order.
+ date: Date when the order was placed.
+ time: Time when the order was placed.

4. Order Details Dataset
+ order_details_id: Unique identifier for each order detail.
+ order_id: Identifier linking the order to the order details.
+ pizza_id: Identifier linking the order detail to the pizza.
+ quantity: Number of pizzas ordered.
