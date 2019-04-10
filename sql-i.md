## Creating Tables

- [Data Types](http://www.postgresqltutorial.com/postgresql-data-types/)
  - What is the difference between `CHAR(n)`, `VARCHAR(n)` and `TEXT`?
  - What are the three kinds of integers?
  - What are the three types of floating-point numbers?
  - What does `SERIAL` do in Postgres? (use the link under Related Tutorials)
- What is the syntax for [creating a new table](http://www.postgresqltutorial.com/postgresql-create-table/)?
- On postgres.devmountain.com, create a student table with this schema:
  ```
  id - primary key serial
  first_name - varchar(255)
  hometown - varchar(255)
  fun_fact - text
  ```

## [Inserting Data](http://www.postgresqltutorial.com/postgresql-insert/)

- What is the syntax for inserting values into a table?
- Insert the following data into the student table from above:

  ```
  first_name: 'Eric'
  hometown: 'Dallas'
  fun_fact: NULL

  first_name: 'James'
  hometown: 'Dallas'
  fun_fact: 'Postgres is progress.'
  ```

## [Updating Data](http://www.postgresqltutorial.com/postgresql-update/)

- What is the syntax for updating existing values in a table?
- Update Eric's `fun_fact` to be `'I love SQL'` using his `first_name`.

## [Querying Data](http://www.postgresqltutorial.com/postgresql-select/)

### Syntax

- How do you select all columns from a table?
- How do you select 2 specific columns from a table?
- What does `DISTINCT` do?
- What does `ORDER BY` do?
- Practice: Get all the information we currently have in the student table, sorted by `id`, with the highest `id` first.

### Filtering Data

- What are 4 comparison operators in PostgreSQL? (Hint: Look in the `WHERE` section. There are many more than 4 available.)
- What do `BETWEEN` and `IN` do?
- How do you check for `NULL` values? (Hint: it's not `= NULL` or `!= NULL`)
- What does `LIMIT` do?
- What do each of these aggregate functions do?
  - `min()`
  - `max()`
  - `sum()`
  - `avg()`
  - `count()`
- What do `LIKE` and `ILIKE` do?
- What's the difference between `%` and `_` with `ILIKE`?
