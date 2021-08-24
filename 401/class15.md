##  Event Driven Architecture : 

- Event-driven architecture (EDA) is a software architecture paradigm promoting the production, detection, consumption of, and reaction to events. 

![img](https://media-exp1.licdn.com/dms/image/C5112AQFtkMSuM5oUkg/article-cover_image-shrink_720_1280/0/1582384474532?e=1635379200&v=beta&t=X3a5o_UHzhtpCx0wi6RULdyHUJ6ZbHPQ6x7ClZMG7uc)

### Review, Research, and Discussion

1. What’s the difference between a FIFO and a standard queue?

- Standard queues provide at-least-once delivery, which means that each message is delivered at least once. FIFO queues provide exactly-once processing, which means that each message is delivered once and remains available until a consumer processes it and deletes it".


2. How can the server be assured a message was properly received? 
- these Messages are stored on the queue until they are processed and deleted. Each message is processed only once, by a single consumer.

![img](https://image.slidesharecdn.com/m05restapisandmq-190506110350/95/rest-apis-and-mq-12-638.jpg?cb=1557141036)
 
 3. What classic design pattern is best represented by event driven programming? 
 - end to end

 ![img](https://hazelcast.com/wp-content/uploads/2020/02/20_EventDrivenArchitecture.png)

 4. How do you test an event driven system?
  events for inputs and events for outputs. Another by-product of a decoupled architecture is often an absence of mocks and stubs in the service test code, which stems from inherent ‘unawareness’ the service has of other services
 ![img](https://files.speakerdeck.com/presentations/a6a0e980ef7c4358976f05c61560ea2e/slide_4.jpg)


 ### Document the following Vocabulary Terms 

1. FIFO Queue =>  In computing and in systems theory, FIFO is a method for organising the manipulation of a data structure where the oldest entry, or "head" of the queue, is processed first
2. Pub/Sub =>enables you to create systems of event producers and consumers, called publishers and subscribers.

### Preparation Materials
- AWS SNS and SQS


SNS =>  is a web service that makes it easy to set up, operate, and send notifications from the cloud. It provides developers with a highly scalable, flexible, and cost-effective capability to publish messages from an application and immediately deliver them to subscribers or other applications 
![img](https://docs.aws.amazon.com/sdk-for-javascript/v2/developer-guide/images/code-samples-sns.png)

aws => 
Develop and deploy applications with the AWS SDK for JavaScript. The SDK provides first class TypeScript support and makes it easy to call AWS services using idiomatic JavaScript APIs to build Node. js, web, and mobile web applications.
![img](https://camo.githubusercontent.com/bac146e328345e5e1f8b238c4beeb656f2d3ce84169b35da57a4e80babf42bcb/68747470733a2f2f73332e616d617a6f6e6177732e636f6d2f736f686e6275636b65742f4e6f64652b506970656c696e652b43686172742e706e67)