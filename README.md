Hotel Billing System

A simple Hotel Order & Billing Management System built using Python (OOP) and SQL Server.
This project demonstrates secure database connectivity, order handling, and dynamic bill generation.

Features

--Fetch menu from SQL Server
--Take multiple customer orders
--Generate formatted bill with grand total
--Insert orders into database


Technologies Used--
Python 3
pyodbc
Microsoft SQL Server
ODBC Driver 17

Database Tables
menu(Table)--
id (PK)
name
price

orders(Table)--
id (PK)
menu_id (FK)
quantity
price
created_date

