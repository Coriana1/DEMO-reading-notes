# What is OAuth
1. What is OAuth?
  - An open standard protocol for secure and delegated access to resources, such as user data, from one website or application to another. 
2. Give an example of what using OAuth would look like.
  - If you wanted to use an online file-sharing service like Dropbox to store and share your files. Instead of creating a new account with a new password, you have the option to sign up using your Microsoft account.
3. How does OAuth work? What are the steps that it takes to authenticate the user?
  - User initiates the process, Application requests access, User grants access, Authentication server issues token, Token is sent to application, Application accesses user's resources
4. What is OpenID?
  - An open standard protocol that allows users to authenticate themselves across different websites or applications without having to create and remember multiple usernames and passwords

## Authorization and Authentication flows
1. What is the difference between authorization and authentication?
  - Authentication is the process of verifying who you are, while authorization is the process of verifying what you are allowed to do.
2. What is Authorization Code Flow?
  - An OAuth 2.0 grant type used for obtaining access tokens on behalf of users. 
3. What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
  - An extension of the standard Authorization Code Flow in OAuth 2.0 that provides an additional layer of security against certain types of attacks.
4. What is Implicit Flow with Form Post?
  - Used to authenticate clients (such as web applications) and users to access protected resources on a server.
5. What is Client Credentials Flow?
  - An OAuth 2.0 grant type used for server-to-server authentication.
6. What is Device Authorization Flow?
  - An OAuth 2.0 flow that is used to authenticate devices that have limited input capabilities (such as smart TVs or Internet of Things devices) and to provide an easier authentication experience for users.
7. What is Resource Owner Password Flow?
  - An OAuth 2.0 grant type used for user authentication and authorization, where the client application obtains an access token by presenting the user's username and password directly to the authorization server.