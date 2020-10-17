# Review

- Define three related pieces of data in a possible application. An example for a store application might be Product, Category and Department. Describe the constraints and rules on each piece of data and how you would relate these pieces to each other. For example, each Product has a Category and belongs in a Department.

table Product has id, name, and category_id whick refrance to the category table.

Department has many pruducts but product realted to only one departmen

- What is the advantage of an ORM, like Mongoose?

It has the data validation built into it(requirements of what data you will allow to be added or to update your database).

- How does the repository pattern compare with an ORM?

THe ORM is an implementation detail of the Repository. The ORM just makes it easy to access the db tables in an OOP friendly way.

The repository abstract persistence access, whatever storage it is.

When making a repository/facade, what flexibility do you gain?

1. improve the readability and usability of a software library by masking interaction with more complex components behind a single (and often simplified) API

2. provide a context-specific interface to more generic functionality (complete with context-specific input validation)

3. serve as a launching point for a broader refactor of monolithic or tightly-coupled systems in favor of more loosely-coupled code

Name 3 cloud based NoSQL Databases

1. Apache Cassandra
2. MongoDB
3. OrientDB

# Terms

- lifecycle:Software Development Life Cycle (SDLC) is a process used by the software industry to design, develop and test high quality softwares. The SDLC aims to produce a high-quality software that meets or exceeds customer expectations, reaches completion within times and cost estimates.

- collections: A grouping of MongoDB documents. A collection is the equivalent of an RDBMS table.

repository pattern: is one of the more popular patterns at the moment. I for one like it, it follows the solid principles and done right it is clean and easy to use.

Middleware(in mogoDB): (also called pre and post hooks) are functions which are passed control during execution of asynchronous functions.

ORM: is a technique that lets you query and manipulate data from a database using an object-oriented paradigm.

# API

API is the acronym for Application Programming Interface, which is a software intermediary that allows two applications to talk to each other. Each time you use an app like Facebook, send an instant message, or check the weather on your phone, you’re using an API.

# POST

The POST verb is most-often utilized to **create** new resources. In particular, it's used to create subordinate resources. That is, subordinate to some other (e.g. parent) resource. In other words, when creating a new resource, POST to the parent and the service takes care of associating the new resource with the parent, assigning an ID (new resource URI), etc.

# GET

The HTTP GET method is used to **read** (or retrieve) a representation of a resource. In the “happy” (or non-error) path, GET returns a representation in XML or JSON and an HTTP response code of 200 (OK). In an error case, it most often returns a 404 (NOT FOUND) or 400 (BAD REQUEST).

# PUT

PUT is most-often utilized for **update** capabilities, PUT-ing to a known resource URI with the request body containing the newly-updated representation of the original resource.

# DELETE

DELETE is pretty easy to understand. It is used to **delete** a resource identified by a URI.
