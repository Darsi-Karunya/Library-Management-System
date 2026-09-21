# Library Management System

## Project Overview

The Library Management System is a DBMS mini project developed using MySQL and MySQL Workbench 8.0 CE. It is designed to manage library members, books, suppliers, fine details, and book issue records using a relational database.

The project demonstrates how related tables can be used to store and retrieve library information efficiently through SQL queries.

## Features

- Manage library member details
- Manage book details
- Store supplier information
- Maintain fine details
- Track book issue and return records
- Use primary and foreign key relationships
- Retrieve data using SQL queries
- Filter records using WHERE conditions
- Perform pattern matching using LIKE
- Use aggregate functions such as COUNT
- Group records using GROUP BY
- Join related tables using JOIN

## Tech Stack

- MySQL
- MySQL Workbench 8.0 CE
- SQL

## Database Tables

The project contains the following tables:

1. `lms_members`
2. `lms_suppliers_details`
3. `lms_fine_details`
4. `lms_book_details`
5. `lms_book_issue`

## Database Concepts Used

- Database and table creation
- Primary Keys
- Foreign Keys
- Data insertion
- SELECT statements
- WHERE clause
- LIKE operator
- COUNT function
- GROUP BY
- JOIN operations
- Data filtering and retrieval

## Setup and Run

### 1. Install MySQL

Install MySQL Server and MySQL Workbench 8.0 CE.

### 2. Open MySQL Workbench

Open MySQL Workbench and connect to the MySQL server.

### 3. Create the Database

Run the SQL script provided in this repository.

```sql
create database library_management;
use library_management;
