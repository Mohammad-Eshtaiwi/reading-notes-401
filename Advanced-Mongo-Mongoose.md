# Advanced Mongo/Mongoose

# Review

Why would a developer choose to make data models?

- Higher quality, Reduced cost ,Quicker time to market.

What purpose do CRUD operations serve?

- refers to all of the major functions that are implemented in relational database applications. Each letter in the acronym can map to a standard Structured Query Language (SQL) statement, Hypertext Transfer Protocol (HTTP) method

What kind of database is Postgres? What kind of database is MongoDB?

- Postgres is relational database, MongooDB NoSQL database

What is Mongoose and why do we need it?

- Mongoose is an Object Data Modeling (ODM) library for MongoDB and Node.js. It manages relationships between data, provides schema validation, and is used to translate between objects in code and the representation of those objects in MongoDB.

## Terms

- database: A database is an organized collection of data, generally stored and accessed electronically from a computer system.

- A data model: is an abstract model that organizes elements of data and standardizes how they relate to one another and to the properties of real-world entities.

- CRUD: refers to all of the major functions that are implemented in relational database applications. Each letter in the acronym can map to a standard Structured Query Language (SQL) statement, Hypertext Transfer Protocol (HTTP) method

- schema :logical collection of database objects. A user owns that owns the schema is known as schema owner.
- sanitize: removing vulgarities & odd symbols from text to removing SQL injection attempts and other malicious code intrusion attempts.

- Structured Query Language (SQL) : is a standard language for storing, manipulating and retrieving data in databases.

- NoSQL databases : are non tabular, and store data differently than relational tables. NoSQL databases come in a variety of types based on their data model. The main types are document, key-value, wide-column, and graph. They provide flexible schemas and scale easily with large amounts of data and high user loads.

- MongoDB: is a general purpose, document-based, distributed database built for modern application developers and for the cloud

- A record: is a data structure that can hold data items of different kinds.
- Document: is a storage for data in NoSql databases
- Object-Relational Mapping (ORM): is a technique that lets you query and manipulate data from a database using an object-oriented paradigm. When talking about ORM, most people are referring to a library that implements the Object-Relational Mapping technique, hence the phrase "an ORM".

# mongodb memory server

This package spins up an actual/real MongoDB server programmatically from node, for testing or mocking during development. By default it holds the data in memory. A fresh spun up mongod process takes about 7Mb of memory. The server will allow you to connect your favorite ODM or client library to the MongoDB server and run integration tests isolated from each other.
