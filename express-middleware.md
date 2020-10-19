# Express Middleware

Middleware functions are functions that have access to the request object (req), the response object (res), and the next middleware function in the application’s request-response cycle. The next middleware function is commonly denoted by a variable named next.

## Built-in middleware

- express.static serves static assets such as HTML files, images, and so on.
- express.json parses incoming requests with JSON payloads. NOTE: Available with Express 4.16.0+
- express.urlencoded parses incoming requests with URL-encoded payloads. NOTE: Available with Express 4.16.0+

Use third-party middleware to add functionality to Express apps.

```
var express = require('express')
var app = express()
var cookieParser = require('cookie-parser')

// load the cookie-parsing middleware
app.use(cookieParser())

```

# review

**What’s the difference between PUT and PATCH?**

PUT: If user can update all or just a portion of the record

PATCH: If user can only update a partial record

**Provide links to 3 services or tools that allow you to “mock” an API for development like json-server**

REST API , Express, HTTP methods

SOAP is a standardized protocol that sends messages using other protocols such as HTTP and SMTP. The SOAP specifications are official web standards, maintained and developed by the World Wide Web Consortium (W3C).

Compare and contrast SOAP and ReST

REST was created to address the problems of SOAP. Therefore it has a more flexible architecture. It consists of only loose guidelines and lets developers implement the recommendations in their own way.

# Terms

- SOAP: specification for exchanging structured information in the implementation of web services in computer networks.

- REST verbs : POST,GET,PUT,DELETE and PATCH

- CRUD Verbs: Create,Read,Update,Delete and Modify
