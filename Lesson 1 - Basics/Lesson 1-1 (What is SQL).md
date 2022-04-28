# Intro To SQL

## Navigation
- **[[#Introduction to SQL]]**
	- [[#What is SQL]]
	- [[#What Can SQL do]]
- **[[# SQL Syntax]]**
	- [[#Database Tables]]
	- [[#SQL Statements]]
- **[[# Some of The Most Important SQL Commands]]**



# Introduction to SQL
#### What is SQL?
- SQL stands for Structured Query Language.
- SQL lets you access and manipulate databases.
- SQL became a standard of the American National Standards Institute (ANSI) in 1986, and of the International Organization for Standardization (ISO) in 1987.

#### What Can SQL do?
- SQL can execute queries against a database.
- SQL can retrieve data from a database.
- SQL can insert records in a database.
- SQL can update records in a database.
- SQL can delete records from a database.
- SQL can create new databases.
- SQL can create new tables in a database.
- SQL can create stored procedures in a database.
- SQL can create views in a database.
- SQL can set permissions on tables, procedures, and views.


# SQL Syntax
#### Database Tables
- A database most often contains one or more tables.
- Each table is identified by a name (e.g. "Customers" or "Orders").
- Tables contain records (rows) with data.

#### SQL Statements
- Most of the actions you need to perform on a database are done with SQL statements.
- The following SQL statement selects all the records in the "Customers" table:

``` SQL
select * from Customers;
```


# Some of The Most Important SQL Commands
-   `CREATE DATABASE` - creates a new database
-   `SELECT` - extracts data from a database
-   `UPDATE` - updates data in a database
-   `DELETE` - deletes data from a database
-   `INSERT INTO` - inserts new data into a database
-   `ALTER DATABASE` - modifies a database
-   `CREATE TABLE` - creates a new table
-   `ALTER TABLE` - modifies a table
-   `DROP TABLE` - deletes a table
-   `CREATE INDEX` - creates an index (search key)
-   `DROP INDEX` - deletes an index


##### `note :`
- SQL keywords are NOT case sensitive: `select` is the same as `SELECT`
- Tables names and columns name is case sensitive