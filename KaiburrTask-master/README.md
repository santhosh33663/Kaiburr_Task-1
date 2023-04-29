# KaiburrTask
Java Servlet Programs

*__Task 1. Java REST API example.__

Implement an application in java which provides a REST API with endpoints for searching,
creating and deleting “server” objects:

● __GET servers__. Should return all the servers if no parameters are passed. When server id
is passed as a parameter - return a single server or 404 if there’s no such a server.

● __PUT a server__. The server object is passed as a json-encoded message body. Here’s an
example:

> {
> “name”: ”my centos”,
> “id”: “123”,
> “language”:”java”,
> “framework”:”django”
> }

● __DELETE a server__. The parameter is a server ID.

● __GET (find) servers by name__. The parameter is a string. Must check if a server name
contains this string and return one or more servers found. Return 404 if nothing is found.
“Server” objects should be stored in MongoDB database.

Be sure that you can show how your application responds to requests using postman, curl or
any other HTTP client.*
