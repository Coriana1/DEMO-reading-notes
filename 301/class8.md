# API Design Best Practices
1. What does REST stand for?
  - Representational State Transfer
2. REST APIs are designed around a ____.
  - Set of standard HTTP methods (such as GET, POST, PUT, and DELETE) and the representation of resources through URIs (Uniform Resource Identifiers).
3. What is an identifier of a resource? Give an example.
  - A URI *(Uniform Resource Identifier)* that uniquely identifies the resource and provides a way to access it. (used as a string)
      *ex: https://anexample.com/api/class/1234*
4. What are the most common HTTP verbs?
  - GET, POST, PUT, DELETE, HEAD, OPTION, PATCH, TRACE, CONNECT
5. What should the URIs be based on?
  - The resources they identify - should provide a way to access these resources
6. Give an example of a good URI.
  - https://anotherexample.com/api/shop/1234
7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
  - A big number of little request that have to be made for a single operation or to retrieve a single resource. It can be an issue becasuse it can cause bad performance with all the request combined with the network latency. 
8. What status code does a successful GET request return?
  - 200 OK
9. What status code does an unsuccessful GET request return?
  - 404 Not Found, 401 Unauthorized, 400 Bad Request, 403 Forbidden, 500 Internal Server Error
10. What status code does a successful POST request return?
  - 201 Created
11. What status code does a successful DELETE request return?
  - 204 No Content