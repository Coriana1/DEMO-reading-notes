# AWS SQS vs SNS
1. What is the difference betweeen SQS and SNS?
  - SQS is a fully managed message queuing service that enables decoupling of application components and asynchronous communication. SNS is a publish-subscribe messaging service. It enables the distribution of messages to multiple subscribers, known as endpoints.
2. What are some use cases for both SNS and SQS?
  - SQS: Batch processing, Workflow orchestration SNS: Mobile push notifications, Email notifications

## AWS SNS and SQS
1. Describe how to use SQS and SNS in a “fanout” pattern.
  - SNS is used to distribute messages to multiple SQS queues or endpoints. 
  Here's how it works:
Create an SNS topic and subscribe the desired SQS queues or endpoints to the topic.
When a message is published to the SNS topic, it is automatically delivered to all subscribed SQS queues or endpoints.
Each SQS queue or endpoint can process the message independently and perform specific actions based on the received message.
2. Explain how “push notifications” work, using SNS.
  - Set up SNS to act as a notification service for your application.
    Register the mobile devices or endpoints with SNS.
    When an event occurs that requires a push notification, publish a message to the SNS topic associated with the registered devices.
    SNS delivers the message to the registered devices, typically using platform-specific push notification services like Apple Push Notification Service (APNS) or Firebase Cloud Messaging (FCM).
    The devices receive the push notification and display it to the user.

## SQS and SNS Basics
1. How might a large scale, distributed application make use of a Queue system like SQS?
  - Load leveling, Fault tolerance

## Reflection
1. What are your learning goals after reading and reviewing the class README?
  - Learn how to architect scalable and reliable applications on AWS