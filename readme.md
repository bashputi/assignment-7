# PostgreSQL Basics

---

## 1. What is PostgreSQL?
PostgreSQL is an open-source relational database management system (RDBMS) known foe its robustness, extensibility, and support for complex data handling. It supports SQL querying and JSON (non-relational) data and includes features for full-text search, geospatial queries, and custom functions.

## 2. What is the purpose of a database schema in PostgreSQL?
A database schema in postgreSQL is a namespace within a database that helps organize tables, views, functions, and other database objects. It provides a logical structure to group related database objects, making management easier and improving control over access. Multiple schemas can exist within a single database, allowing for data and functional separation.

## 3: Explain the primary key and foreign key concepts in PostgreSQL.
- **Primary Key**: A primary key is a unique identifier for each record in a table. Each table can have only one primary key, which ensures that each row in the table is unique.
-**Foreign Key**: A foreign key is a field (or group of fields) in one tables that uniquely indentifies a row of another table. Foreign keys enforce a link between tables, establishing relationships and maintaining referential integrity.

## 4: What is the difference between the VARCHAR and CHAR data types?
-**VERCHAR**: A variable-length string data type that can store up to a specified number of characters. It uses only as much space as necessary for each entry, making it space-efficient.
-**CHAR**: A fixed-length string data type. It always reserves the specified number of characters, padding with spaces if necessary. It can be less efficient in terms of storage but is useful for data with a consistent length requirement.