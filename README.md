# 📚 SQL Project: Online Book Store

This project involves building and querying a small relational database for an online book store using **SQL**. It is designed to demonstrate your ability to handle **data relationships**, **query optimization**, and perform both **basic** and **advanced analysis** on sales and customer data.

---

## 🗂️ Dataset Overview

The project is based on **three CSV files** which represent core entities of the book store:

| File Name       | Description                          | Key Columns             |
|----------------|--------------------------------------|-------------------------|
| `Books.csv`     | Information about books              | `Book_ID`               |
| `Customers.csv` | Customer details                     | `Customer_ID`           |
| `Orders.csv`    | Book orders placed by customers      | `Book_ID`, `Customer_ID`|

🔗 These files are **interconnected via foreign keys** such as `Customer_ID` and `Book_ID`.

---

## 📋 Table Requirements

- Each table must have **at least one common column** with another table.
- Common columns must have **matching names and data types**.

---

## 🧮 Basic SQL Queries

1. Retrieve all books in the "Fiction" genre.
2. Find books published after the year 1950.
3. List all customers from Canada.
4. Show orders placed in **November 2023**.
5. Retrieve the total stock of books available.
6. Find details of the **most expensive book**.
7. Show all customers who ordered more than 1 quantity of a book.
8. Retrieve all orders where the **total amount** exceeds $20.
9. List all genres available in the `Books` table.
10. Find the book with the **lowest stock**.
11. Calculate the **total revenue** generated from all orders.

---

## 🔍 Advanced SQL Queries

1. Retrieve the **total number of books sold** for each genre.
2. Find the **average price** of books in the "Fantasy" genre.
3. List customers who have placed **at least 2 orders**.
4. Find the **most frequently ordered** book.
5. Show the **top 3 most expensive Fantasy books**.
6. Retrieve the **total quantity** of books sold by each author.
7. List the cities where customers who spent over $30 are located.
8. Find the customer who **spent the most** on orders.
9. Calculate the **stock remaining** after fulfilling all orders.

---

## 🛠️ Tech Stack

- **Database**: SQL (Any relational DBMS like MySQL, PostgreSQL, SQLite)
- **Tools**: DB Browser for SQLite / MySQL Workbench / pgAdmin
- **Languages**: SQL only

---

## 🚀 How to Run

1. Import the `.csv` files into your SQL database.
2. Ensure tables are connected using correct foreign keys.
3. Run the queries in your SQL editor or command-line tool.
4. Verify output and modify queries as needed for optimization.

---

## ✅ Learning Outcomes

- Understanding of **relational database design**
- Mastery of **SQL joins**, filters, and aggregate functions
- Real-world skills in **data analysis and reporting**

---

## 📎 Related Files

- `Books.csv`
- `Customers.csv`
- `Orders.csv`
