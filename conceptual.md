### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?  
  A relational database management system

- What is the difference between SQL and PostgreSQL?  
  SQL server is a database management system. PostgreSQL is an advanced version of SQL which provides support
  to different functions of SQL like foreign keys.

- In `psql`, how do you connect to a database?  
  you can either press **\c** and the database or directly from the terminal you can type in _psql_ and the database
  to start psql already in the database.

- What is the difference between `HAVING` and `WHERE`?  
  A **HAVING** clause is like a **WHERE** clause, but applies only to groups as a whole, whereas the **WHERE** clause applies to individual rows.
  
- What is the difference between an `INNER` and `OUTER` join?  
  The __*inner*__ join will only display information relative to both the joining tables, __*outer*__ join will display all information relative to one or both tables no matter if it is relevant to both.

- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?  
  __*left*__ and __*right*__ differ in whether the first or second table get to display all their information even the unmatched rows.

- What is an ORM? What do they do?  
  __*Object Relational Mapping*__ (**ORM**) is a technique used in creating a "bridge" between object-oriented programs and relational databases. You use the ORM as the layer that connects object oriented programming (**OOP**) to relational databases.

- What are some differences between making HTTP requests using AJAX 
  and from the server side using a library like `requests`?  
  The biggest difference is that server side allows us to keep our api information secure, also having the client have to make each individual http request limits the possibilities for the client as he might need to use a paid api page and it will block him. the client facing api would be faster for displaying to the client but slower to save it to the database.

- What is CSRF? What is the purpose of the CSRF token?  
  A **CSRF** token is a secure random token that is used to prevent CSRF attacks. The token needs to be unique per user session and should be of large random value to make it difficult to guess. A CSRF secure application assigns a unique CSRF token for every user session.

- What is the purpose of `form.hidden_tag()`?  
  The form. hidden_tag() template argument generates a hidden field that includes a token that is used to protect the form against CSRF attacks. All you need to do to have the form protected is include this hidden field and have the SECRET_KEY variable defined in the Flask configuration.