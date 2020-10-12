# Data Modeling & NoSQL Databases

# Review

Name 3 advantages to Test Driven Development?

1. Better program design and higher code quality
2. Detailed project documentation
3. refactor with confident

In what case would you need to use beforeEach() or afterEach() in a test suite?

- beforeEach() is run before each test in a describe and used to map the data before sent it to test.
- afterEach() is run after each test in a describe and used to clean up stuff like close opened file.

What is one downside of Test Driven Development?

- it can cause over engineering.
- it cost time and effort.
- sometime when the design is not clear or not robust you will reimplement your tests and cost you more

What’s the primary difference between ES6 Classes and Constructor/Prototype Classes?

- ES6 Classes is slmply cleaner and simpler

Name a use case for a static method

- for example a classroom has a number of chairs that increment each time new student will join

- Write an example of a Higher Order function and describe the use case it solves

- Math.random() is a higher order function that used to genarate a random value

# Terms

Functional programming: is a programming paradigm, meaning that it is a way of thinking about software construction based on some fundamental, defining principles.

Pure function: is a function where the return value is only determined by its input values, without observable side effects.

higher-order function: is a function that does at least one of the following: takes one or more functions as arguments (i.e. procedural parameters) or returns a function as its result.

Immutable objects: for which none of the state can be changed become important when you are dealing with concurrency, the ability for more than one processor in your computer to operate on that object at the same time.

object : a real world entity

Object-oriented programming (OOP): is a computer programming model that organizes software design around data, or objects, rather than functions and logic. An object can be defined as a data field that has unique attributes and behavior.

Class: is a template definition of the method s and variable s in a particular kind of object .

Prototypes: are the mechanism by which JavaScript objects inherit features from one another. In this article, we explain how prototype chains work and look at how the prototype property can be used to add methods to existing constructors.

Super: a keyword in the class thar reffer to the perent class

Inheritance: is the mechanism of basing an object or class upon another object

constructor: is a special method that is used to initialize objects. The constructor is called when an object of a class is created. It can be used to set initial values for object attributes

Instance: is a concrete occurrence of any object, existing usually during the runtime of a computer program. Formally, "instance" is synonymous with "object" as they are each a particular value (realization)

context: It refers to the object to which a function belongs.

this: reffer to the context or the scope

Test Driven Development (TDD): is the idea of strting your code with test cases and then write code

Continuous integration (CI): is the practice of merging all developers' working copies to a shared mainline several times a day.

Unit tests: are typically automated tests written and run by software developers to ensure that a section of an application (known as the "unit") meets its design and behaves as intended.

# NoSQL databases

NoSQL databases (aka "not only SQL") are non tabular, and store data differently than relational tables. NoSQL databases come in a variety of types based on their data model. The main types are document, key-value, wide-column, and graph. They provide flexible schemas and scale easily with large amounts of data and high user loads.
