## Creating Tables

- Define these datatypes in PostgreSQL:

  - NULL
  - INTEGER
  - DECIMAL
  - FLOAT
  - TEXT
  - VARCHAR(n)

- What does SERIAL do in Postgres? (Note: in chinook.ml this will be INTEGER PRIMARY KEY AUTOINCREMENT)

- What is the syntax for creating a new table?

- On <http://postgres.devmountain.com> , create a student table with this schema:
  - id - integer - primary key autoincrement
  - first_name - varchar(255)
  - hometown - varchar(255)
  - fun_fact - text

## Inserting Data (Section 9)

- What is the syntax for inserting values into a table?

- Insert the following data into the student table from above:
  
  ```
  first_name: 'Eric'
  hometown: 'Dallas'
  fun_fact: NULL
  ```
  
  ```
  first_name: 'James'
  hometown: 'Dallas'
  fun_fact: 'Postgres is progress.'
  ```

## Updating Data (Section 9)

- What is the syntax for updating existing values in a table?

- Update Eric's fun_fact to be 'I love SQL' using his id.

## Querying Data (Section 2 and 3)

### Syntax

- How do you select all columns from a table?

- How do you select 2 specific columns from a table?

- What does DISTINCT do?

- What does ORDER BY do?

- Practice: Get all the information we currently have in the student table, sorted by id, with the highest id first.

### WHERE clauses

- What are 4 comparison operators in PostgreSQL? (Hint: Look in the WHERE section)

- What do AND, OR and IN do?

- How do you check for NULL values? (Hint: it's not = NULL or != NULL)

- What does LIMIT do?

- What do each of these aggregate functions do?

  - min()
  - max()
  - sum()
  - avg()
  - count()

- How does LIKE work?

- What's the difference between % and \_ with LIKE?
