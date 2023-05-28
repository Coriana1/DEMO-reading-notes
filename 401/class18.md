# AWS API Gateway Overview
1. What is Amazon API Gateway?
  - A fully managed service provided by AWS that allows developers to create, publish, and manage APIs (Application Programming Interfaces) for their applications. 
2. Why is Amazon API Gateway an important part of the Serverless ecosystem?
  - It provides a secure, scalable, and managed infrastructure to expose APIs and handle the routing of requests to the appropriate backend services.
3. How does API Gateway integrate with other AWS services?
  - AWS Lambda: API Gateway can directly invoke Lambda functions in response to API requests, allowing serverless processing of data and business logic.
    AWS Cognito: API Gateway integrates with Cognito for authentication and authorization, enabling secure access control for APIs.
    AWS DynamoDB: API Gateway can interact with DynamoDB to store and retrieve data, providing a seamless connection between APIs and the database.
    AWS S3: API Gateway can be used to directly access and serve static content stored in S3 buckets.

## AWS API Gateway
1. What are the some benefits of using Amazon API Gateway?
  - Easy API creation and management, Scalability, Analytics and monitoring
2. What two API types might you choose from?
  - REST APIs, WebSocket APIs

## AWS DynamoDB Guide
1. What is DynamoDB?
  - Fully managed NoSQL database offering seamless scalability, automatic data replication, and low-latency access to data, making it well-suited for applications that require high throughput and low latency.
2. Under what circumstances would you recommend DynamoDB over MongoDB?
  - When scalability is a primary concern

## AWS DynamoDB
1. Explain to a non-technical friend how DynamoDB works.
  - Think of it as a giant table where you can store information. DynamoDB is designed to be very fast and can handle a large amount of data. It also automatically takes care of storing multiple copies of your data to ensure it's safe and available even if something goes wrong. DynamoDB is great for applications that need to handle a lot of data quickly and reliably.

## Dynamoose
1. What is Dynamoose?
  - A library or tool that makes it easier to work with DynamoDB in your applications. It provides a simple and convenient way to interact with DynamoDB without having to write complex code.
2. What are some key features of Dynamoose?
  - Object-Data Mapping (ODM), Schema validation, Query and CRUD operations, Integration with other frameworks

## Reflection
1. What are your learning goals after reading and reviewing the class README?
  - I want to learn how to effectively use these services to build scalable and reliable applications.