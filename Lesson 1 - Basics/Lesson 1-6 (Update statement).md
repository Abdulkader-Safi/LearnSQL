# SQL Update statement

## Navigation
- **[[#Example table]]**
- **[[#Update Statement]]**
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


# Update Statement
#### Update One data
``` SQL
UPDATE Customers SET Name = 'Alfred' WHERE ID = 10002;
```
this statement will update the name in the secound row

the table will be updated into 
| ID      | First_Name  | Email                |
| ----    | ----        | ----                 |
| 10001   | abdulkader  | abdulkader@gmail.com |
| 10002   | Alfred      | Kay@gmail.com        |
| 10004   | Dalton      | Dalton@gmail.com     |
| 10005   | abdulkader  | abdulkader2@gmail.com|


#### Update multi data
``` SQL
UPDATE Customers SET Name = 'Alfred', Email = 'alfred@gmail.com' WHERE ID = 10002;
```
this statement will update the name in the secound row

the table will be updated into 
| ID      | First_Name  | Email                |
| ----    | ----        | ----                 |
| 10001   | abdulkader  | abdulkader@gmail.com |
| 10002   | Alfred      | alfred@gmail.com     |
| 10004   | Dalton      | Dalton@gmail.com     |
| 10005   | abdulkader  | abdulkader2@gmail.com|

