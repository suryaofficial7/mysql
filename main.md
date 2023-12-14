1.Creating Database :
create database database_name;
-------------------------------------------------------------------
2.delete table 
drop database database_name;
-------------------------------------------------------------------
3.cretae table 

-- Syntax for creating a table
CREATE TABLE table_name (
    column1 datatype,
    column2 datatype,
    column3 datatype,
    ...
);

-- Example:
CREATE TABLE employees (
    employee_id INT PRIMARY KEY,
    first_name VARCHAR(50),
    last_name VARCHAR(50),
    salary INT
);
-------------------------------------------------------------------
4.Insertion 
-- Syntax for inserting a single row
INSERT INTO table_name (column1, column2, column3, ...)
VALUES (value1, value2, value3, ...);

-- Example:
INSERT INTO employees (first_name, last_name, salary)
VALUES ('John', 'Doe', 50000);
-------------------------------------------------------------------
5.deleting
-- Syntax for deleting data from a table
DELETE FROM table_name WHERE condition;

-- Example:
DELETE FROM employees WHERE employee_id = 101;
-------------------------------------------------------------------
6.updating
-- Syntax for updating data in a table
UPDATE table_name
SET column1 = value1, column2 = value2, ... WHERE condition;

-- Example:
UPDATE employees
SET salary = 55000 WHERE employee_id = 101;
-------------------------------------------------------------------
