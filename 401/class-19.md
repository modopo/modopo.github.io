# Reading Class 19

AWS SQS vs SNS

1) They serve difference purposes. SQS is a queue that stores messages, which allows you to decouple components in a cloud-base application. SNS publishes and subscribes messaging service that interact to multiple recipients/subscribers at once.

2) It allows developers to easily create and manage APIs without having to worry about the underlying infrastructure.

3) Credit card transaction can utilize both SQS and SNS. Any type of log processing from multiple sources can be collected and processed in real-time.

AWS SNS and SQS

1) In a fanout pattern, messages are sent to a single topic in SNS, and then SNS broadcasts the message to multiple SQS queues. Each queue has its own set of consumers that can process the messages independently.

2) Push notifications using SNS involve registering endpoints such as mobile devices or web browsers with SNS, creating an SNS topic, subscribing the endpoints to the topic, publishing messages to the topic, and delivering the push notifications to the subscribed endpoints.

SQS and SNS Basics

1) Decoupling components, scaling, batch processing, tolerance (if something fails, the queue still exist and be processed elsewhere), and asynchronous processing ability are some things a large scale distributed application uses to ensure it's running smoothly.