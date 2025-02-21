# Bookstore-Management-System
This project is a database-driven system designed to manage a bookstore's inventory, customers, and orders. It includes SQL queries to retrieve, analyze, and manipulate data related to books, customers, and orders. The project demonstrates basic and advanced SQL querying techniques for data analysis and management.

# Database Schema
The database consists of three main tables:

1. Books
Book_ID (Primary Key)
Title
Author
Genre
Published_Year
Price
Stock

2. Customers
Customer_ID (Primary Key)
Name
Email
Phone
City
Country

3. Orders
Order_ID (Primary Key)
Customer_ID (Foreign Key)
Book_ID (Foreign Key)
Order_Date
Quantity
Total_Amount
