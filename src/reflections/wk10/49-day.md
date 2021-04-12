4/8/2021

Read Dotnet WebAPI's > Welcome to SQL, and answer the following questions

In a SQL table, what is the difference between information in a row and information in a column?
Columns contain the column name, data type, and any other attributes for the column. Rows contain the records or data for the columns.


Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.
CREATE TABLE characters(
  name VARCHAR(255) NOT NULL,
  description VARCHAR(255) NOT NULL,
  age VARCHAR(255),
  id int NOT NULL
);

What is the difference between the following statements:

DELETE FROM table_name;
DROP TABLE table_name;

Delete would delete the one thing from the table, drop table completely gets rid of the entire table.