##Securing Passwords
1. Explain to a non-technical friend how you would safely hash and store a password.
  - * We use a special algorithm to turn the password into a unique and irreversible hash.
  * We add a random salt to each password before hashing to make the process more secure.
  * We store the hashed password and the salt securely in our system
2. What is Bcrypt?
  - A trusted and widely-used algorithm for secure password hashing.  
3. Why might you use something like Bcrypt?
  - Used to securely store passwords by protecting against unauthorized access, defending against brute-force and dictionary attacks, utilizing salted password hashes, and resisting parallel computing attacks

## Basic Auth
1. What is Basic Authentication?
  - A simple and widely-used method for authenticating users in web-based applications or APIs, part of the HTTP protocol and involves sending the user's credentials (username and password) with each request to the server.
2. What properties are necessary in the header of a Basic Auth request?
  - Authorization: This property holds the authentication information and has the format "Basic <credentials>". The word "Basic" indicates the type of authentication being used. The <credentials> part represents the Base64-encoded string of the username and password, separated by a colon ":". The username and password are combined as "<username>:<password>" and then Base64-encoded.
3. How are username:password in Basic Auth encoded?
  - The username and password are combined into a single string separated by a colon (":") and then Base64-encoded

## OWASP auth cheatsheet
1. Define the authentication process to a non-technical recruiter.
  - Authentication ensures that only authorized individuals can access protected systems or applications, safeguarding sensitive data and maintaining the integrity of digital resources.
2. How should your error messaging respond (both HTTP and HTML)? Why?
  - Should be designed to provide useful and meaningful information to users, developers, and administrators. For HTTP with status code, error descirptions, and consistency and for HTML with user friendly messages, clear instructaions and consistent design. To provide enough information to dignose and troubleshoot the issue for develops and admins while giving user friendly/helpful messages to end users for both.

## Reflection 
1. What are your learning goals after reading and reviewing the class README?
- 