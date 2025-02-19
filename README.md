# Introduction to SQL
SELECT * FROM Customers;
# SQL Syntax
SELECT * FROM Customers;
# SQL SELECT Statement
SELECT CustomerName, City FROM Customers;
SELECT column1, column2, ...
FROM table_name;
# SQL SELECT DISTINCT Statement
SELECT DISTINCT Country FROM Customers;
# SQL WHERE Clause
SELECT * FROM Customers
WHERE Country='Mexico';
# SQL ORDER BY Keyword
SELECT * FROM Products
ORDER BY Price;
# SQL AND Operator
SELECT *
FROM Customers
WHERE Country = 'Spain' AND CustomerName LIKE 'G%';
# SQL OR Operator
SELECT *
FROM Customers
WHERE Country = 'Germany' OR Country = 'Spain';
# SQL NOT Operator
SELECT * FROM Customers
WHERE NOT Country = 'Spain';
# SQL INSERT INTO Statement
INSERT INTO Customers (CustomerName, ContactName, Address, City, PostalCode, Country)
VALUES ('Cardinal', 'Tom B. Erichsen', 'Skagen 21', 'Stavanger', '4006', 'Norway');
# SQL NULL Values
SELECT CustomerName, ContactName, Address
FROM Customers
WHERE Address IS NULL;
# SQL UPDATE Statement
UPDATE Customers
SET ContactName = 'Alfred Schmidt', City= 'Frankfurt'
WHERE CustomerID = 1;
# SQL DELETE Statement
DELETE FROM Customers WHERE CustomerName='Alfreds Futterkiste';
