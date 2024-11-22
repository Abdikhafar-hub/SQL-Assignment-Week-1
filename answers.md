Components of a DBMS (Database Management System)
Database Engine: The core service for storing, processing, and securing data. It provides an interface between the physical data and end users.
Database Schema: Defines the structure of the database including tables, fields, data types, relationships, and constraints.
Query Processor: Interprets and executes database queries written in SQL, optimizing their execution for performance.
Transaction Manager: Ensures data integrity and handles operations like commit and rollback in a multi-user environment.
Database Access Language: Provides tools for creating, retrieving, and managing data.
Database Administrator Tools: Utilities for managing the database, including user management, backup, and recovery.
Data Dictionary: Metadata storage that contains information about the database structure, users, and permissions.
Relational Database
A relational database organizes data into structured tables consisting of rows and columns. Each row represents a unique record, and each column holds data for a specific attribute.

Examples:

MySQL
PostgreSQL
Oracle Database
Microsoft SQL Server
Classifications of SQL
Data Definition Language (DDL):

Deals with the structure of the database.
Examples: CREATE, ALTER, DROP.
Data Manipulation Language (DML):

Used for managing data within tables.
Examples: INSERT, UPDATE, DELETE, SELECT.
Data Control Language (DCL):

Manages user permissions and access to the database.
Examples: GRANT, REVOKE.
Difference Between Primary Key and Foreign Key
Primary Key: A unique identifier for each record in a table. It must contain unique values and cannot have nulls.
Foreign Key: A column that establishes a relationship between two tables by referencing the Primary Key of another table.
Entity-Relationship Diagram (ERD)
An ERD is a visual representation of entities, their attributes, and the relationships between them in a database system. It helps in designing and modeling database structures.

Advantages of Relational Databases
Data Integrity: Ensures accuracy and consistency of data.
Flexibility: Easy to modify and expand the database structure.
Data Relationships: Efficient handling of data relationships using keys.
Querying Capability: Supports powerful and standardized querying using SQL.
Four Types of Data Types in Tables
Integer: Stores whole numbers (e.g., INT, SMALLINT).
String: Stores text (e.g., VARCHAR, CHAR).
Date/Time: Stores date and time values (e.g., DATE, DATETIME).
Boolean: Stores true/false values (BIT, BOOLEAN).
Purpose of a DBMS
A DBMS manages and organizes data efficiently. Its main purposes include:

Ensuring data consistency, integrity, and security.
Enabling data access for multiple users simultaneously.
Simplifying data querying and reporting.
Supporting backup, recovery, and transaction management.






