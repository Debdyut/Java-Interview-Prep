# Database Interview Questions
## Question Bank 1

1. <strong>What are views? Can we perform CRUD operations on views?</strong><br/>
    Views is nothing but a virtual table, we can create a view by joing 2 or more tables with or without filter criteria based on our need. Yes we can perform CRUD operations on a simple view that is on a single tabled view, but if it is a complex view then we can not perform CRUD operations on it.

2. <strong>What is cartesian product?</strong><br/>
    The cartesian product also referred to as a cross-join, returns all the rows in all the tables listed in the query.

3. <strong>What is an outer-join?</strong><br/>
    An outer join is used to return results by combining rows from 2 or more tables. But unlike an inner join, the outer join will return every row from one specified table, even if the join condition fails.

4. <strong>Difference between clustered and non-clustered indices.</strong><br/>
    | Clustered Index | Non-Clustered Index |
    | --------------- | ------------------- |
    | Clustered Index is faster. | Non-clustered index is smaller. |
    | Clustered index requires less memory for operations. | Non-clustered index requires more memory for operations. |
    | In clustered index, index is the main data. | In non-clustered index, index is the copy of the data. |
    | A table can have only one clustered index. | A table can have multiple non-clustered index. |
    | Clustered index has inherent ability of storing data on the disk. | Non-clustered index does not have the inherent ability of storing data on the disk. |
    | Clustered index store pointers to block not data. | Non-clusted index store both value and a pointer to actual row that holds data. |