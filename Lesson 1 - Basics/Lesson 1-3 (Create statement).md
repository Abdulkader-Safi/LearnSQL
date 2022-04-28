# SQL Create statement

## Navigation
- **[[#Create Database]]**
- **[[#Create Table]]**
- **[[#SQL Data Types]]**
	- [[#String Data Types]]
	- [[#Numeric Data Types]]
	- [[#Date and Time Data Types]]


# Create Database
``` SQL
create database myDatabase;
```
this statment will create a database called `myDatabase` on RDBMS of your choice.


# Create Table
``` SQL
create table Customers(
	ID int identity(10000 , 1),
	Name varchar(10) not null,
	Email Varchar(20),
);
```
this statment will create a table called `Customers`.

| ID      | First_Name  | Email                |
| ----    | ----        | ----                 |
|         |             |                      |
|         |             |                      |



# SQL Data Types
#### String Data Types
|Data type    |Description                    |Max size                |Storage                  |
| ----        | ----                          | ----                   | ----                    |
|char(n)      |Fixed width character string   |8,000 characters        |Defined width            |
|varchar(n)   |Variable width character string|8,000 characters        |2 bytes + number of chars|
|varchar(max) |Variable width character string|1,073,741,824 characters|2 bytes + number of chars|
|text         |Variable width character string|2GB of text data        |4 bytes + number of chars|
|nchar        |Fixed width Unicode string     |4,000 characters        |Defined width x 2        |
|nvarchar     |Variable width Unicode string  |4,000 characters        |                         |
|nvarchar(max)|Variable width Unicode string  |536,870,912 characters  |                         |
|ntext        |Variable width Unicode string  |2GB of text data        |                         |


#### Numeric Data Types
|Data type   |Description                                                              | Storage  |
| ----       | ----                                                                    | ----     |
|bit         |Integer that can be 0, 1, or NULL                                        |          |
|int         |Allows whole numbers between -2,147,483,648 and 2,147,483,647            |4 bytes   |
|decimal(p,s)|d precision and scale numbers. Allows numbers from -10^38 +1 to 10^38 –1.|5-17 bytes|

#### Date and Time Data Types

|Data type |Description                                                 | Storage  |
| ----     | ----                                                       | ----     |
|date      |Store a date only. From January 1, 0001 to December 31, 9999|3 bytes   |
|time      |Store a time only to an accuracy of 100 nanoseconds         |3-5 bytes |


##### `note :`
- that not all SQL Data Types available but those are the most important and the most used.