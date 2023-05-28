# nosql vs sql

1. What type of database is the best fit for the complex query intensive environment?
  - Columnar Database OR Hybrid Analytical Database (HTAP) - they both can efficiently handling large amounts of data and executing complex analytical queries with high performance.
2. What type of database is the best fit for hierarchical data storage?
  - Hierarchical Database - excel at representing and querying data with a predefined and fixed hierarchical structure
3. Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend.
  -SQL databases work well for smaller datasets and when data relationships are well-defined, just like a well-organized library with a librarian. NoSQL databases are better suited for handling larger datasets and providing fast access to specific information, resembling a big room of books without strict organization rules.

## sql modeling techniques
1. Among data tables, what is a one-to-many relationship and how do we “relate” them?
  - Use a foreign key in the table representing the "many" side of the relationship.
      * This establishes the link between the two tables and allows us to retrieve related data using join operations in SQL queries.
2. Prior to designing your relational database, it might be useful to **create a diagram** of the database tables and their relationships.
3. Explain the difference between a primary and foreign key.
  - Primary key uniquely identifies a record within a table, while a foreign key establishes a relationship between two tables by referencing the primary key of another table.

## sql vs nosql
1. How do we treat keywords and parameters differently in SQL syntax?
  - Keywords are part of the language itself and have predefined meanings, while parameters are variables that hold values provided by the user or the application during execution.
2. Define normalization within the context of schemas and data.
  - process in database design that involves organizing and structuring data in a way that reduces redundancy and dependency. You can achieve better data organization, flexibility, and maintainability and it helps to avoid data inconsistencies, update anomalies, and improves the overall efficiency of data retrieval and manipulation operations.
3. Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.
  - A **one-to-one** relationship represents a unique match, a **one-to-many** relationship represents a parent-child association, and a **many-to-many** relationship represents a mutual connection where multiple entities are associated with multiple others.