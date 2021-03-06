### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?
  PostgreSQL is a powerful, open source object-relational database system that uses and extends the SQL language combined with many features that safely store and scale the most complicated data workloads. 

- What is the difference between SQL and PostgreSQL?
  SQL is a standard language for storing, manipulating and retrieving data in databases. PostgreSQL is a database system that uses and extends the SQL language combined with many features that safely store and scale the most complicated data workloads. 

- In `psql`, how do you connect to a database?
  \c DB_NAME

- What is the difference between `HAVING` and `WHERE`?
  WHERE Clause is used to filter the records from the table or used while joining more than one table. HAVING Clause is used to filter the records from the groups based on the given condition in the HAVING Clause. 

- What is the difference between an `INNER` and `OUTER` join?
  Inner joins result in the intersection of two tables, whereas outer joins result in the union of two tables.

- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?
  LEFT (OUTER) JOIN: Returns all records from the left table, and the matched records from the right table
  RIGHT (OUTER) JOIN: Returns all records from the right table, and the matched records from the left table

- What is an ORM? What do they do?
  An object-relational mapper (ORM) is a code library that automates the transfer of data stored in relational database tables into objects that are more commonly used in application code.

- What are some differences between making HTTP requests using AJAX 
  and from the server side using a library like `requests`?
  Making HTTP requests using AJAX is for client side to request data from server side. From the server side, using a library like 'requests' can make response with the request from client side.

- What is CSRF? What is the purpose of the CSRF token?
  Cross-site request forgery (also known as CSRF) is a web security vulnerability that allows an attacker to induce users to perform actions that they do not intend to perform. 
  A CSRF token is a unique, secret, unpredictable value that is generated by the server-side application and transmitted to the client in such a way that it is included in a subsequent HTTP request made by the client. When the later request is made, the server-side application validates that the request includes the expected token and rejects the request if the token is missing or invalid.

- What is the purpose of `form.hidden_tag()`?
  The form.hidden_tag() template argument generates a hidden field that includes a token that is used to protect the form against CSRF attacks. All you need to do to have the form protected is include this hidden field and have the SECRET_KEY variable defined in the Flask configuration. 
