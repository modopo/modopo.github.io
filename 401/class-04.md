# Reading Class 04

NoSQL vs SQL

1) SQL DB is best suited for complex queries.

2) NoSQL DB is best for hierarchical data storage.

3) SQL is vertically scalable, which means that if there is a need to increase the load to a single server, the hardware can be upgraded to accommodate the increase in load. NoSQL is horizontally scalable, which means that if there is a need to increase the load, multiple servers can be added to the pool to handle the increase in load.

SQL Modeling Techniques

1) One to many relationship is the relationship of one entry in a table related to many different entries in a separate table.

2) model a diagram

3) The primary key is the unique identifier of the entry in the table, while a foreign key is a unique identifier to another entry in a different table.

Express Routing

1) Keywords are capitalized and the parameters are lowercase. Keywords are the main 'methods' for SQL while parameters are used to add options to these methods, like filter for a specific argument. 

2) Normalizing the data forces the data to adhere to a specific schema. For the data to be entered into the table, it needs the specific columns.

3) One to one relationship is binding, since there's only one other item related to your current item. One to many relationship is one item relating to many items in another table. Many to many relatnship is mutliple items in the current table can relate to many other items in another table.