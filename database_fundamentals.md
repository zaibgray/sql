# Database Fundamentals

## 1. Before Starting

Now we are learning SQL

Before that we learned:

- Python
- Numpy
- Pandas
- Data Visualization
- Data Analysis Process

## 2. Importance of Data

We are living in the age where DATA is new oil.

- Computers -> Came -> Works -> Data
- Internet -> Came -> Works -> Data
- AI -> Came -> Works -> Data

All that work with data and all the data store in databases, So to work with database and program the database we must know SQL

## 3. What are Databases?

A Database is a shared collection of logically related data and description of these data, desinged to meet the information needs of an organization

### Usage

**Data Storage:** A database is used to store large amounts of structured data, making it easily accessible, searchable, and retrievable.

**Data Analysis:** A database can be used to perform complex data anaylsis, generate reports, and provide insights into the data

**Record Keeping:** A database is often used to keep track of important records, such as financial trasactions, customer information, and inventory levels.

**Web Applications:** Databases are an essential component of many web applicatins, providing dynamic content and user management.

**Opertions on Database:** CRUD

- Create
- Reterive
- Update
- Delete

## 4. Properties of an Ideal Database

1. **Integrity:** mean Accurate and Consistent

2. **Availability:** 24X7, there should be zero down time

3. **Security:** Database must be secure

4. **Independent of Application:** Database should be desing in a why it can communicate other languages.

5. **Concurrency:** It should be able to handel millions of requests

## 5. Types of Databases

1. **Relational Databases**
Also known as SQL databases, these databases use a relational model to organize data into tables with rows and columns.
2. **NoSQL Databases**
These databases are designed to handle large amounts of unstructured or semi-structured data, such as documents, images, or videos. (MongoDB)
3. **Column Databases**
These databases store data in columns rather than rows, making them well-suited for data warehousing and analytical applications. (Amazon Redshift, Google BigQuery)

    - If you want to learn more about Row vs Column Databasese then [clik here](https://dataschool.com/data-modeling-101/row-vs-column-oriented-databases/)

4. **Graph Databases**
These databases are used to store and query graph-structured data, such as social network connections or recommendation systems. (Neo4j, Amazon Neptune)
5. **Key-value databases**
These databases store data as a collection of keys and values, making them well-suited for caching and simple data storage needs (Redis and Amazon DynamoDB)

## 6. Relational Databases

Also known as SQL databases, these databases use a relational model to organize data into tables with rows and columns.

    - Table = Relation
    - Attribute = Column  = Field
    - Row = Tuple = Record
    - No of rows is called Cardinality of the relation
    - No of columns is called Degree of the relation
    - Missing Value = NULL
    - Domain = What kind of value we can store
        - Example: Name Attribute can store any string, and this is called Domain

## 7. What is a DBMS

- Main thing is database and to run database we use software wich is called DBMS (Database Management System)
- It control Database
- **Flow of Data:** Users -> Application -> DBMS -> Operating System -> Hardware

## 8. Core Functionalities of a DBMS

- **Data Management:** Store, retrieve and modify data
- **Integrity:** Maintain accuracy of data
- **Concurrency:** Simultaneous data access for multiple users
- **Transaction:** Modification to database must either be successful or must not happen at all
- **Security:** Access to authorized users only
- **Utilities:** Data import/export, user management, backup, logging

## 9. Practical

MySQL

- MySQL Workbanch
- Appache XAMPP

## 10. Database Keys

## 11. Cardinality of Relationships

## 12. Drawbacks of Databases
