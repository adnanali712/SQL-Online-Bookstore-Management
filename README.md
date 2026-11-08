# 📚 Online Bookstore Database Management System (SQL)

## 📌 Project Overview

The **Online Bookstore Database Management System** is a SQL-based project developed using PostgreSQL to manage and analyze an online bookstore's operations.

The project focuses on managing book information, customer details, and customer orders while performing SQL queries to extract meaningful business insights.

It demonstrates practical SQL skills, including database creation, table relationships, filtering, joins, aggregate functions, grouping, and advanced queries.

## 🎯 Project Objectives

- Create and manage an online bookstore database.
- Store book, customer, and order information.
- Retrieve data using SQL queries.
- Analyze book sales and revenue.
- Identify customer purchasing patterns.
- Calculate book stock and remaining inventory.
- Generate insights using SQL queries.

## 🛠️ Technologies Used

- **Database:** PostgreSQL
- **SQL Tool:** pgAdmin 4
- **Language:** SQL

## 🗄️ Database Structure

The project consists of three main tables:

### 1. Books Table

Stores information about books.

| Column | Description |
|---|---|
| Book_ID | Unique book identifier |
| Title | Book title |
| Author | Book author |
| Genre | Book category |
| Published_Year | Publication year |
| Price | Book price |
| Stock | Available stock |

### 2. Customers Table

Stores customer information.

| Column | Description |
|---|---|
| Customer_ID | Unique customer identifier |
| Name | Customer name |
| Email | Customer email |
| Phone | Customer phone number |
| City | Customer city |
| Country | Customer country |

### 3. Orders Table

Stores customer order information.

| Column | Description |
|---|---|
| Order_ID | Unique order identifier |
| Customer_ID | References Customers table |
| Book_ID | References Books table |
| Order_Date | Date of order |
| Quantity | Number of books ordered |
| Total_Amount | Total order amount |

## 🔗 Table Relationships

- Books → Orders (One-to-Many)
- Customers → Orders (One-to-Many)

Primary keys and foreign keys are used to establish relationships between the tables.

## 📊 SQL Concepts Implemented

### Basic SQL Queries
- SELECT
- WHERE
- DISTINCT
- ORDER BY
- LIMIT
- BETWEEN

### Aggregate Functions
- SUM()
- AVG()
- COUNT()

### Joins
- INNER JOIN
- LEFT JOIN

### Grouping and Filtering
- GROUP BY
- HAVING

### Advanced SQL Operations
- COALESCE()
- Subqueries and multi-table analysis
- Data aggregation
- Inventory calculations
- Revenue analysis

## 💡 Business Questions Answered

### Basic Analysis

1. Retrieve all books belonging to the Fiction genre.
2. Find books published after 1950.
3. Identify customers from Canada.
4. Retrieve orders placed in November 2023.
5. Calculate the total stock of available books.
6. Find the most expensive book.
7. Identify orders with quantities greater than one.
8. Retrieve orders with a total amount exceeding $20.
9. Find all available book genres.
10. Identify the book with the lowest stock.
11. Calculate total revenue generated from orders.

### Advanced Analysis

1. Calculate the total number of books sold for each genre.
2. Find the average price of Fantasy books.
3. Identify customers who placed at least two orders.
4. Find the most frequently ordered book.
5. Retrieve the top three most expensive Fantasy books.
6. Calculate total books sold by each author.
7. Identify cities where customers placed orders exceeding $30.
8. Find the customer who spent the most money.
9. Calculate remaining book stock after fulfilling orders.

## 📈 Key Insights

The SQL queries help generate insights into:

- Total bookstore revenue.
- Best-selling books and genres.
- Customer purchasing behavior.
- Top-spending customers.
- Author-wise book sales.
- Book inventory and remaining stock.
- Popular book categories.

## 📂 Project Structure

```text
Online-Bookstore-SQL-Project/
│
├── sql project.sql
└── README.md
```

## 🚀 How to Run the Project

1. Install PostgreSQL on your system.
2. Open pgAdmin 4.
3. Create or connect to your PostgreSQL server.
4. Open the SQL project file.
5. Execute the database creation script.
6. Import the required data into the Books, Customers, and Orders tables.
7. Execute the SQL queries to explore the results.

## 🎓 Skills Demonstrated

- PostgreSQL Database Management
- SQL Query Writing
- Data Retrieval and Filtering
- Relational Database Design
- Data Analysis
- Joins and Aggregate Functions
- Business Data Analysis
- Problem-Solving

## 👨‍💻 Author

**Md Adnan Ali**

Aspiring Data Analyst | SQL | Power BI | Excel | Python

GitHub: [adnanali712](https://github.com/adnanali712)

---

⭐ If you find this project useful, consider giving this repository a star!
