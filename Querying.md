# Querying

## DATABASE  
A **database** is a structured collection of data, organized to allow easy creation, reading, updating, and deletion of information.

---

## Database Management System (DBMS)  
A **DBMS** is software that lets you create, manage, and interact with databases.  
**Examples:** MySQL, Oracle, PostgreSQL, SQLite.

---

## SQL (Structured Query Language)  
**SQL** is the standard language used to communicate with databases. It lets you create, read, update, and delete data.

---

## Example Commands  
```bash
ls -l longlist.db     # Lists the database file details  
sqlite3 longlist.db   # Opens the SQLite database file named 'longlist.db'
KEYWORDS & DESCRIPTIONS
SELECT
Retrieves data from one or more columns in a table.

LIMIT
Restricts the number of rows returned by a query.

WHERE
Filters records based on specified conditions.

NULL
Represents missing or undefined data in a database.

Operators: AND, OR, ()
Combine multiple conditions in the WHERE clause.

AND requires both conditions to be true.

OR requires at least one condition to be true.

Parentheses () group conditions to control evaluation order.

LIKE
Used for pattern matching in strings.

% wildcard represents zero or more characters.

BETWEEN ... AND ...
Filters records within a specific range (inclusive).

ORDER BY
Sorts query results by one or more columns.

ASC for ascending order (default).

DESC for descending order.

Aggregate Functions
Functions that operate on multiple rows and return a single value.

COUNT(column)
Counts the number of non-NULL values in a column.

AVG(column)
Calculates the average (mean) value of a numeric column.

Use ROUND() to round the average to a certain number of decimal places.

Use AS to rename the output column.

MIN(column)
Finds the minimum value in a column.

MAX(column)
Finds the maximum value in a column.

SUM(column)
Adds up all the values in a numeric column.

Basic SQL Query Structure
sql
Copy
Edit
SELECT column1, column2, ...
FROM table_name
WHERE condition
ORDER BY column_name ASC|DESC
LIMIT number_of_rows;
SELECT specifies which columns to return.

FROM indicates the table to query.

WHERE filters rows based on conditions.

ORDER BY sorts the output.

LIMIT restricts how many rows are returned.

Opening a SQLite Database
To open a database file named filename.db:

bash
Copy
Edit
sqlite3 filename.db
This opens an interactive SQLite prompt where you can run SQL queries.
