# SQL Select statement

## Navigation
- **[[#Example table]]**
- **[[#Select all Statement]]**
- **[[#Select  column Statement]]**
- **[[#Select DISTINCT Statement]]**
- **[[#Select Top Statement]]**


# Example table
table Customers.
| ID      | First_Name  | Email                |
| ----    | ----        | ----                 |
| 10001   | abdulkader  | abdulkader@gmail.com |
| 10002   | Kay         | Kay@gmail.com        |
| 10004   | Dalton      | Dalton@gmail.com     |
| 10005   | abdulkader  | abdulkader2@gmail.com|
| 10006   | Jennifer    | Jennifer@gmail.com   |
| 10007   | Carlos      | Carlos@gmail.com     |
| 10008   | Samir       | samir@gmail.com      |


# SQL Select Statement
#### Select  all Statement
``` SQL
select * from Customers;
```
this statement select all columns from the table Customers

this statment will return:
| ID      | First_Name  | Email                |
| ----    | ----        | ----                 |
| 10001   | abdulkader  | abdulkader@gmail.com |
| 10002   | Kay         | Kay@gmail.com        |
| 10004   | Dalton      | Dalton@gmail.com     |
| 10005   | abdulkader  | abdulkader2@gmail.com|
| 10006   | Jennifer    | Jennifer@gmail.com   |
| 10007   | Carlos      | Carlos@gmail.com     |
| 10008   | Samir       | samir@gmail.com      |

#### Select  column Statement
``` SQL
select First_Name, Email from Customers;
```
this statement select only First_Name, Email columns from the table Customers

this statment will return:
| First_Name  | Email                |
| ----        | ----                 |
| abdulkader  | abdulkader@gmail.com |
| Kay         | Kay@gmail.com        |
| Dalton      | Dalton@gmail.com     |
| abdulkader  | abdulkader2@gmail.com|
| Jennifer    | Jennifer@gmail.com   |
| Carlos      | Carlos@gmail.com     |
| Samir       | samir@gmail.com      |

#### Select DISTINCT Statement
``` SQL
select DISTINCT ID, First_Name from Customers;
```
- The `SELECT DISTINCT` statement is used to return only distinct (different) values.
- Inside a table, a column often contains many duplicate values; and sometimes you only want to list the different (distinct) values.

this statment will return:
| ID      | First_Name  |
| ----    | ----        |
| 10001   | abdulkader  |
| 10002   | Kay         |
| 10004   | Dalton      |
| 10006   | Jennifer    |
| 10007   | Carlos      |
| 10008   | Samir       |


#### Select Top Statement
``` SQL
select top 7 from Customers;
```
- The `SELECT top` statement is used to return only top values.
- and here it will return only top 7 values.

this statment will return:
| ID      | First_Name  | Email                |
| ----    | ----        | ----                 |
| 10001   | abdulkader  | abdulkader@gmail.com |
| 10002   | Kay         | Kay@gmail.com        |
| 10004   | Dalton      | Dalton@gmail.com     |
| 10005   | abdulkader  | abdulkader2@gmail.com|
| 10006   | Jennifer    | Jennifer@gmail.com   |
| 10007   | Carlos      | Carlos@gmail.com     |

