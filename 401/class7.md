# Intro to JWT
1. What is a JSON Web Token (JWT)?
  - A compact, URL-safe means of representing claims between two parties commonly used for authentication and authorization purposes in web applications and APIs.
2. When should we use JSON Web Tokens?
  - Authentication, single-sign-on, authorization and acess control, API authentication and authorixation, mobile applications - if your application requires frequent updates to the user's access or permissions, a different authentication mechanism might be more suitable.
3. Claims are expected in which structural component of a JWT?
  - Payload component

## Are JWTs Secure?
1. If I get a JWT and I can decode the payload, how can we call that secure?
  - By verifying the digital signature of a JWT, you can be confident that the token has not been modified and that the claims contained within it can be trusted
2. If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.
  - must possess or have access to the same secret key or public key to generate and verify the signature.
3. Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.
  - By securely sending and receiving concatenated content and a secret using encryption and decryption, we can ensure that the information remains confidential and cannot be understood by unauthorized individuals.

## JWTs Explained
1. Why use JWT?
  - Stateless and Scalable, Secure Transmission, Authentication and Authorization, Easy Integration, Extensibility
2. JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.
  - JWT's compact and self-contained nature makes it convenient and efficient. It eliminates the need for carrying physical documents or relying on external databases to verify your identity and permissions. It's like having a secure and portable digital pass that simplifies access to specific services, areas, or privileges.
3. What are the three components (the structure) of a JWT signature?
  - These three components (header, payload, and signature) are combined using periods (.) to form a JWT in the format "header.payload.signature"

## Reflection
1. What are your learning goals after reading and reviewing the class README?
  -