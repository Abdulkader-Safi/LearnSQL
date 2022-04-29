# SQL Insert statement

## Navigation
- **[[#Insert one]]**
- **[[#Insert multi]]**


# Insert one
``` SQL
insert into Customers (Name, Email) Values ('Abdulkader', 'abdulkader@gmail.com')
```
this statement will insert one row to our table


# Insert multi
``` SQL
insert into Customers (Name, Email) Values 
			('Abdulkader', 'abdulkader@gmail.com'),
			('Jennifer', 'Jennifer@gmail.com'),
```
this statement will insert multi row, multi data to our table


##### `note :`
- we can not insert data for any variable that use Identity because it is an auto increment it will be auto generate.
- when we use not null we can not insert empty data.
- we can insert more then 2 or 3 row data at the same time
- we use `'` for string or text variable and we do not use it for numbers
