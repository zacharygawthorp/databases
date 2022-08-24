### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?

PostgreSQL is an open source object-relational database system that uses and extends the SQL language combined 
with many features that safely store and scale the most complicated data workloads.

- What is the difference between SQL and PostgreSQL?

PostgreSQL is an object-relational database, while SQL is a relational database system.

- In `psql`, how do you connect to a database?

In terminal run psql 'database name'

- What is the difference between `HAVING` and `WHERE`?

The WHERE clause is used to filter the records from the table based on the specified condition.
The HAVING clause is used to filter record from the groups based on the specified condition.

- What is the difference between an `INNER` and `OUTER` join?

Inner join results in the intersection of two tables, whereas outer join results in the union of two tables.

- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?

LEFT OUTER join returns all rows from the left table and matching records between both tables, whereas RIGHT OUTER join returns all the rows from the right table and matching records.

- What is an ORM? What do they do?

AN ORM provides an object-oriented layer between relational databases and object-oriented programming languages without having to write SQL queries.

- What are some differences between making HTTP requests using AJAX 
  and from the server side using a library like `requests`?

Client-Side requests- Don't have to involve Flask in the API. Can be faster
Server-Side requests - Easier for server to store/process the data. Need password to access API.

- What is CSRF? What is the purpose of the CSRF token?

Cross-Site Request Forgery. A CSRF is a secure random token that is used to prevent CSRF attacks. 

- What is the purpose of `form.hidden_tag()`?

It generates a hidden field that includes a token that is used to protect the form against CSRF attacks.