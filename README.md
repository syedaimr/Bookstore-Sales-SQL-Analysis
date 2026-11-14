# Bookstore Sales Data Analysis Using SQL

## Project Overview

This project focuses on analyzing bookstore sales data using PostgreSQL.

The objective is to explore book inventory, customer information, and order transactions to answer business-related questions using SQL queries.

The project demonstrates practical SQL skills, including data filtering, aggregation, joins, and data analysis.

## Tools & Technologies

- Database: PostgreSQL
- Query Language: SQL
- Database Tool: pgAdmin / PostgreSQL
- Version Control: GitHub

## Dataset Description

The project contains three datasets:

| Dataset | Description | Records |
|---|---|---:|
| Books | Book details, authors, genres, prices, and stock | 500 |
| Customers | Customer names, contact information, and locations | 500 |
| Orders | Order dates, quantities, and transaction amounts | 500 |

## Database Structure

The project uses three relational tables:

1. **Books:** Stores book information.
2. **Customers:** Stores customer information.
3. **Orders:** Stores customer purchase transactions.

Primary and foreign keys are used to establish relationships between the tables.

## Business Questions

The analysis explores the following questions:

1. Retrieve books belonging to the Fiction genre.
2. Find books published after 1950.
3. Identify customers from Canada.
4. Retrieve orders placed in November 2023.
5. Calculate the total available book stock.
6. Identify the most expensive book.
7. Find orders containing more than one book.
8. Retrieve orders with a total amount exceeding $20.
9. Identify all available book genres.
10. Find the book with the lowest stock.
11. Calculate total revenue.
12. Calculate books sold by genre.
13. Find the average price of Fantasy books.
14. Identify customers who placed at least two orders.
15. Find the most frequently ordered book.
16. Identify the three most expensive Fantasy books.
17. Calculate book quantities sold by author.
18. Explore customer locations associated with orders above $30.
19. Identify the highest-spending customer.
20. Calculate remaining stock after fulfilling orders.

## SQL Concepts Used

- SELECT and WHERE
- ORDER BY and LIMIT
- DISTINCT
- Aggregate Functions: SUM, AVG, COUNT
- GROUP BY and HAVING
- INNER JOIN and LEFT JOIN
- COALESCE
- Primary Keys and Foreign Keys

## Project Folder Structure

```text
bookstore-sales-sql-analysis/
│
├── README.md
├── data/
├── sql/

```

## How to Run This Project

1. Install PostgreSQL on your system.
2. Create a database named `bookstore_db`.
3. Open the SQL files in pgAdmin or your preferred SQL editor.
4. Execute `01_create_tables.sql`.
5. Import the three CSV datasets into their respective tables.
6. Execute the analysis SQL files.
7. Review the query results.

## Learning Outcomes

Through this project, I practiced:

- Creating relational databases and tables.
- Working with structured datasets.
- Writing SQL queries to answer business questions.
- Joining multiple tables.
- Using aggregate functions to analyze sales.
- Understanding customer purchasing patterns and book inventory.

## Author
Syeda Imroz
Created as a beginner SQL Data Analytics portfolio project.
