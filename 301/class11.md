# Fill in the chart below with five differences between SQL and NoSQL databases:
SQL	NoSQL
 Data Structure:  
  SQL databases are relational - they store data in tables with rows and columns that have predefined relationships. 
  NoSQL databases - are non-relational and do not follow a rigid schema, allowing for more flexibility in data structure.

Query Language: 
  SQL databases use SQL to retrieve and manipulate data. 
  NoSQL databases - do not rely on SQL but instead have their own query language that is specific to the database.

Scalability: 
  SQL databases are vertically scalable - they can handle more traffic and data by increasing the hardware of the server. 
  NoSQL databases are horizontally scalable - they can handle more traffic and data by adding more servers to the database cluster.

Data Consistency: 
  SQL databases are known for their ACID (Atomicity, Consistency, Isolation, and Durability) compliance, which ensures that data is consistent and accurate even in the face of errors or failures. 
  NoSQL databases often sacrifice some consistency for scalability and flexibility.

Use Cases: 
  SQL databases are well-suited for applications that require a strict schema and complex querying capabilities, such as financial applications or enterprise resource planning systems. 
  NoSQL databases are better suited for applications with unstructured or rapidly changing data, such as social media platforms or Internet of Things (IoT) devices.	 
 	 
1. What kind of data is a good fit for an SQL database?
  - Financial data, heathcare, customer relationship management (CRM), inventory management, e-commerce
2. Give a real world example.
  -Facebook
3. What kind of data is a good fit a NoSQL database?
  - Unstructured or semi-structured data, which is data that does not have a clear schema or a well-defined set of fields and relationships.
4. Give a real world example.
  - Amazon DynamoDB
5. Which type of database is best for hierarchical data storage?
  - Hierarchical database management system (DBMS) 
6. Which type of database is best for scalability?
  - NoSQL

## sql vs nosql (Video)
1. What does SQL stand for?
  - Structured Query Language
2. What is a relational database?
  - Type of database that organizes data into one or more tables with a unique key identifying each row or record. 
3. What type of structure does a relational database work with?
  - A tabular or table-like structure to organize and store data. 
4. What is a ‘schema’?
  - A logical container that holds and organizes database objects, such as tables, views, indexes, and procedures.
5. What is a NoSQL database?
  - A type of database that differs from traditional relational databases in that it does not use the structured query language (SQL) to manage and retrieve data. 
6. How does it work?
  - Data Storage, querying, scalability, types of NoSQL database - rovide a more flexible and scalable approach to data storage and retrieval, making them a popular choice for modern applications that require high levels of scalability, performance, and flexibility.
7. What is inside of a MongoDB database?
  - A database consists of one or more collections that hold data - similar to a table in a relational database, but collections are schemaless, which means that the documents in a collection do not have to have the same structure or fields.
8. Which is more flexible - SQL or MongoDB? and why.
  - MongoDB because it does not have a predefined schema
9. What is the disadvantage of a NoSQL database?
   - Limited community support, Limited ACID compliance, Difficulty with complex queries, Limited data analysis capabilities, Lack of Standardization