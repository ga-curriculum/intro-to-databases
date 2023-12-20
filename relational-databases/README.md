# ![Relational Databases](./assets/hero.png)

**Learning objective:** By the end of this lesson, students will be able to define what a relational database is, what SQL is, and the elements that make up a SQL database.

## Introduction to Relational Databases

A relational database is a type of database management system (DBMS) that organizes data into tables, which consist of rows and columns. This structure is based on the principles of the relational model, introduced by E.F. Codd in 1970. In a relational database, data is stored in a structured way to establish relationships between different entities.

## SQL (Structured Query Language)

**SQL (Structured Query Language)**, typically pronounced "sequel" or "Ess-Que-Ell", is a programming language used to CRUD data stored in a relational database.

SQL syntax is similar to the English language.

Although SQL is fairly standard, it can vary slightly depending on the RDBMS (Relational Database Management System). For example, *SQLite* implements fewer SQL commands than *PostgreSQL*.


## Tables, Rows, and Columns

The primary container for data in a relational database is a table:

![image of a table](./assets/tktktable.png)

A row in a table represents a single instance of the data entity.

Each column represents a specific attribute or field of the data being stored, and it defines the type of data that can be stored in that particular position