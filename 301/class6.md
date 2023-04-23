How I explained REST to my brother

1. Who is Roy Fielding? 
  -A computer scientist and one of the principal authors of the HTTP specification, also known for his work on the Representational State Transfer (REST) architectural style.
2. Why don’t the techniques that we use in this class work well when we need to be able to talk to all of the machines in the world? 
  - These techniques are not sufficient because the Internet is a vast, decentralized network with a diverse range of devices and communication protocols. One of the main challenges of communicating with all of the machines in the world is addressing. 
3. What is the HTTP protocol that Fielding and his friends created?
  - HTTP **Hypertext Transfer Protocol** - The foundation of the World Wide Web, allowing clients to browse the web, request resources *(webpages or images)* from web servers, and to recieve response in the form of HTML and other types of content. 
4. What does a GET do?
  - Retrieve a resource from a web server - it's asking the server to return a representation of a specific resource, such as a web page, image, or file.
5. What does a POST do?
  - Submit data to a web server - it's asking the server to accept and store the data enclosed in the request message body
6. What does PUT do?
  - Updates an existing resource on a web server - it's asking the server to replace the existing resource with the data enclosed in the request message body
7. What does PATCH do?
  - artially update an existing resource on a web server - it is asking the server to modify only the specified fields or attributes of the resource, leaving the rest of the resource unchanged.