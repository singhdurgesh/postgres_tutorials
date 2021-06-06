# Basic Postgres Statements for Quering a Database


## SELECT

- Mostly used statement while doing Database work is quering the database using SELECT statement. It has many clauses.
- ';' is not 
- First Specify the column names seperated with comma(,)
- And then write the table name from which data is being queried after the **FROM** keyword.
    - SELECT first_name FROM customer;
- Semicolon ';', at the end of statement is not a part of SQL statment instead it is used to signal the PostgreSQL the end of the SQL statment. It is also used to seperate two SQL statements. 

### FROM clause
**From** clause is optional for quering databe
    - "SELECT 7 + 9;" is also a valid SQL statements.

### FROM => SELECT

### With Expressions
- SELECT first_name || ' ' || last_name from customer;
    || is a concatenation operator.

### Column Aliases using AS clause
- SELECT column_name/expression AS alias_name FROM table_name;
    - SELECT first_name, last_name AS surname FROM customer;
    - SELECT first_name || ' ' || last_name as full_name FROM customer;

### ORDER BY





