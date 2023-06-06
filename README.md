# 8-Weeks-SQL-Challenge-
case study link -> https://8weeksqlchallenge.com/case-study-1

## Danny's Diner SQL Project
This repository contains SQL queries for analyzing customer data for Danny's Diner, a fictional restaurant. The queries address various questions related to customer spending, menu items, membership, and loyalty points.

## Data Description
The data used in this project includes the following tables:

sales: Contains information about customer orders, including the customer ID, product ID, order date, and price.
members: Contains information about customers who have joined the membership program, including the customer ID and join date.
menu: Contains information about the menu items, including the product ID, product name, and price.

## Queries

The project includes SQL queries that answer the following questions:

1. What is the total amount each customer spent at the restaurant?
2. How many days has each customer visited the restaurant?
3. What was the first item from the menu purchased by each customer?
4. What is the most purchased item on the menu and how many times was it purchased by all customers?
5. Which item was the most popular for each customer?
6. Which item was purchased first by the customer after they became a member?
7. Which item was purchased just before the customer became a member?
8 What is the total items and amount spent for each member before they became a member?
9. If each $1 spent equates to 10 points and sushi has a 2x points multiplier, how many points would each customer have?
10 In the first week after a customer joins the program, they earn 2x points on all items - how many points do customer A and B have at the end of January?

## Bonus Questions
In addition to the main queries, the project also includes bonus questions that provide additional insights into the customer data:

Join All The Things: This query combines multiple tables to create a result set that includes the customer ID, order date, product name, price, and a flag indicating whether the customer is a member or not. It helps analyze customer purchases and their membership status.

Rank All The Things: This query extends the previous bonus query by including a ranking column that indicates the rank of the product for each customer. The ranking is only provided for customers who are members; otherwise, it is shown as null. This query helps understand the popularity of menu items among members.
