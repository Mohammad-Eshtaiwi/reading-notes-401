# API Server

## Review

How does route prefixing work with an external routing module?

app.use('/PREFIX_HERE', route)

When routing, what’s the difference between app.get('/data/:id') and app.get('/data/:name')?

- app.get('/data/:id') the parameter name is id

- app.get('/data/:name')the parameter name is name

Explain how Express handles routing conflicts?

Since express evaluates the routes in addition order, you should put the more specific routes first.

What are the ways that a browser can send “data” or request variables to an HTTP server?

using forms or fetch api

## Terms

- Routing: refers to how an application's endpoints (URIs) respond to client requests.

- Route Prefixing: app.use('/PREFIX_HERE', route)

- Request “Body”: is data sent by the client to your API. A response body is the data your API sends to the client.

- Request “Query” : A query string is a part of a uniform resource locator (URL) that assigns values to specified parameters. A query string commonly includes fields added to a base URL by a Web browser or other client application, for example as part of an HTML form.

- Request “Params”: /article/id id is the param here.

## router.param(name, callback)

Adds callback triggers to route parameters, where name is the name of the parameter and callback is the callback function.

## Middleware in mongo

Middleware (also called pre and post hooks) are functions which are passed control during execution of asynchronous functions. Middleware is specified on the schema level and is useful for writing plugins.

## Subdocuments

Subdocuments are documents embedded in other documents. In Mongoose, this means you can nest schemas in other schemas. Mongoose has two distinct notions of subdocuments: arrays of subdocuments and single nested subdocuments.
