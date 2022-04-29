# SQL Delete statement

## Navigation
- **[[#Example table]]**
- **[[#Delete Statement]]**
	- [[#Update One data]]
	- [[#Update multi data]]


# Example table
table Customers.
| ID      | First_Name  | Email                |
| ----    | ----        | ----                 |
| 10001   | abdulkader  | abdulkader@gmail.com |
| 10002   | Kay         | Kay@gmail.com        |
| 10004   | Dalton      | Dalton@gmail.com     |
| 10005   | abdulkader  | abdulkader2@gmail.com|


# Delete Statement
#### Delete One data
``` SQL
delete from Customers where ID = 10001;
```
this statement will delete the row with ID `10001`

| ID      | First_Name  | Email                |
| ----    | ----        | ----                 |
| 10002   | Kay         | Kay@gmail.com        |
| 10004   | Dalton      | Dalton@gmail.com     |
| 10005   | abdulkader  | abdulkader2@gmail.com|

#### Empty the table
``` SQL
delete from Customers;
-- or 
truncate table Customers;
```
this statements will delete all the data in the table Customers

| ID      | First_Name  | Email                |
| ----    | ----        | ----                 |
|         |             |                      |