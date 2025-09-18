📘 Library Management System (MySQL Database)
📌 Overview

This project is a Library Management System implemented in MySQL.
It demonstrates database design using tables, constraints, and relationships.
The system manages students, books, authors, categories, and borrowing transactions.

🎯 Objectives

Design a relational database schema with real-world use case.

Apply Primary Keys, Foreign Keys, NOT NULL, and UNIQUE constraints.

Model relationships:

One-to-Many (Category → Books, Student → Borrowings)

Many-to-Many (Books ↔ Authors)

Implement the schema using SQL statements.

🛠️ Database Schema
Entities:

Students – stores student information.

Categories – book categories.

Authors – book authors.

Books – stores book details.

Book_Authors – links books and authors (many-to-many).

Borrowings – borrowing records.

📂 Project Files

LibraryDB.sql → Contains all SQL statements:

CREATE DATABASE

CREATE TABLE

Relationship constraints

🚀 How to Use

Open MySQL Workbench (or your SQL client).

Run the LibraryDB.sql script.

SOURCE path/to/LibraryDB.sql;


The database LibraryDB will be created with all tables and relationships.

📊 Example Schema Diagram (Simplified)
Students ───< Borrowings >─── Books >── Categories
                 │
                 └── Authors (via Book_Authors)

✨ Deliverables

By completing this assignment, you will have:

A working MySQL database (LibraryDB)

Tables with constraints & relationships

A .sql file ready for submission
