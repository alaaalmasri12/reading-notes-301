#SQL
Structured Query Language is the standard means of manipulating and querying data in relational databases, though with proprietary extensions among the products. The ease and ubiquity of SQL have even led the creators of many “NoSQL” or non-relational data stores the standard SQL commands such as `Select`, `Insert`, `Update`, `Delete`, "Create", and "Drop" can be used to accomplish almost everything that one needs to do with a database.

What Can SQL do?
SQL can execute queries against a database
SQL can retrieve data from a database
SQL can insert records in a database
SQL can update records in a database
SQL can delete records from a database
SQL can create new databases
SQL can create new tables in a database
SQL can create stored procedures in a database
SQL can create views in a database
SQL can set permissions on tables, procedures, and views

### Examples on SQL

## The SQL SELECT Statement

`SELECT column1, column2, ...`
`FROM table_name;`

ex:
`SELECT CustomerName, City FROM Customers;`
## SELECT DISTINCT Syntax
`SELECT DISTINCT column1, column2, ...`
`FROM table_name;`
ex:
`SELECT Country FROM Customers;`

### The SQL WHERE Clause
`SELECT column1, column2, ...`
`FROM table_name`
`WHERE condition;`

ex:
`SELECT * FROM Customers`
`WHERE Country='Jordan';`

### The SQL INSERT INTO Statement

`INSERT INTO table_name (column1, column2, column3, ...)`
`VALUES (value1, value2, value3, ...);`
ex:
`INSERT INTO Customers (CustomerName, ContactName, Address, City, PostalCode, Country)`
`VALUES ('Cardinal', 'Tom B. Erichsen', 'Skagen 21', 'Stavanger', '4006', 'Norway')`

### The SQL UPDATE Statement

`UPDATE table_name`
`SET column1 = value1, column2 = value2, ...`
`WHERE condition;`

ex:
`UPDATE Customers`
`SET ContactName = 'Alaa almasri', City= 'jordan'`
`WHERE CustomerID = 1;`

### The SQL DELETE Statement
`DELETE FROM table_name WHERE condition`;

ex:
`DELETE FROM Customers WHERE CustomerName='Alaa almasri';`
