# Review API Server Build
1. Explain the different between a query string parameter and a path parameter.
  - How they are included in a URL. Query string parameters are added at the end of the URL after a question mark, and they are used to pass data to the server as key-value pairs. Path parameters, on the other hand, are included in the URL path itself and are used to identify specific resources or endpoints.
2. What would our API URL with a path id parameter be given the following information:
  -  **http://our-site.com/v3/stuff/things**
Domain: http://our-site.com
v3
model name: stuff
id: things
3. We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend.
  - Imagine our dynamic API as a digital assistant that communicates with different services in our application. It has a customizable "interface" where we can tell it what we want to do, and it interacts with the appropriate service to fulfill our requests. So, whenever we need to access or modify data, we can simply communicate with this helpful assistant, and it will take care of the rest, making our job easier!

## Review Auth Server Build
1. Describe how you would use middleware to implement basic and bearer auth.
  - Using middleware for basic and bearer auth involves adding a security layer to the API endpoints. For basic auth, the middleware checks if the user's provided credentials match the expected ones, granting access only if they match. For bearer auth, the middleware verifies the user's token, ensuring its validity before allowing access to protected endpoints.
2. Describe the handshake necessary to implement OAuth.
  - First, the client application redirects the user to the OAuth provider's authorization endpoint, where the user provides their consent to grant access. The OAuth provider then redirects the user back to the client application with an authorization code. The client application exchanges this code for an access token and a refresh token by making a request to the OAuth provider's token endpoint. The access token is used to make authorized requests on behalf of the user.
3. Describe how Role Based Access Control works to a non-technical friend.
  - Role-Based Access Control (RBAC) is like organizing a party with different roles for guests. Each role (e.g., host, guest, or organizer) has specific permissions and responsibilities. In the same way, RBAC in software systems assigns roles to users, determining what they can and cannot do. So, depending on their role, users get access to certain parts of the application, ensuring security and a smooth experience for everyone.