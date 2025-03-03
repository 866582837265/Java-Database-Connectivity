# Java-Database-Connectivity
## Overview
This repository provides a simple example of using JDBC (Java Database Connectivity) to interact with a relational database. It demonstrates establishing a connection, executing queries, and handling results using **Java and JDBC**.

## Features
- Connect to a database using JDBC
- Perform CRUD (Create, Read, Update, Delete) operations
- Use PreparedStatement for parameterized queries

## Prerequisites
- Java 8+
- PostgreSQL or any other relational database
- Corresponding JDBC Driver

## Approach
- Load the JDBC Driver: Load the appropriate JDBC driver using Class.forName().
- Establish a Connection: Use DriverManager.getConnection() to establish a connection to the database.
- Create a Statement or Prepared Statement: Create either a Statement or PreparedStatement for executing SQL queries.
- Execute Queries: Use Statement.execute() or PreparedStatement.execute() to execute SQL queries.
- Process Results: Handle the query results using ResultSet.

  
