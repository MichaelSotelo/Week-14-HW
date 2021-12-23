# Week 14 Homework: Web Development #
Overview
In this homework, we will review the many of the concepts and tools covered in the Web Development unit. If needed, refer to the reference sheets provided to you.

# HTTP Requests and Responses #

What type of architecture does the HTTP request and response process occur in?
* Client-Server Architecture

What are the different parts of an HTTP request?
* Request Line, Request Headers, Request Body

Which part of an HTTP request is optional?
* Request Body

What are the three parts of an HTTP response?
* Headers, Status Line, Body

Which number class of status codes represents errors?
* 400s range

What are the two most common request methods that a security professional will encounter?
* GET and POST

Which type of HTTP request method is used for sending data?
* POST

Which part of an HTTP request contains the data being sent to the server?
* Request body

In which part of an HTTP response does the browser receive the web code to generate and style a web page?
* Response body

# Using curl #

What are the advantages of using curl over the browser?
* Manage HTTP Requests/Responses in a repeatable way
* Quickly test HTTP HTTP Requests in a way that can be automated
* Able to to make adjustments as you go
* GUI not necessary to use several protocols

Which curl option is used to change the request method?
* -X

Which curl option is used to set request headers?
* -H

Which curl option is used to view the response header?
* -I

Which request method might an attacker use to figure out which HTTP requests an HTTP server will accept?
* Options

# Sessions and Cookies #

Which response header sends a cookie to the client?


[page content]
What is the response status code?
* 200

What web server is handling this HTTP response?
* Apache Webserver

Does this response have a user session associated to it?
* Yes

What kind of content is likely to be in the [page content] response body?
* Website Code

If your class covered security headers, what security request headers have been included?
* Strict Transport Security

# Monoliths and Microservices #

Answer the following questions about monoliths and microservices:

What are the individual components of microservices called?
* Services

What is a service that writes to a database and communicates to other services?
* API

What type of underlying technology allows for microservices to become scalable and have redundancy?
* Load Balancer

# Deploying and Testing a Container Set #

Answer the following questions about multi-container deployment:

What tool can be used to deploy multiple containers at once?
* Docker

What kind of file format is required for us to deploy a container set?
* .yml

# Databases #

Which type of SQL query would we use to see all of the information within a table called customers?
* SELECT column_name FROM customers

Which type of SQL query would we use to enter new data into a table? (You don't need a full query, just the first part of the statement.)
* INSERT INTO table_name (column_1 column_2 column_3) VALUES (value_1 value_2 value_3)

Why would we never run DELETE FROM <table-name>; by itself?
* The entire table would be deleted 
