# Reading Class 17

AWS S3

1) S3 stands for Simple Storage Service, which is a cloud-based storage service provided by Amazon Web Services (AWS). It allows users to store and retrieve data.

2) Backup and recovery. Content distribution. Web Hosting. Big Data analytics

3) Scalability, where user can scale up the storage as needed. Durability, where the data is stored in multiple regions, and can be available if some hardware fails.

AWS Lambda Basics

1) Lambda is a computing service that allows developers to run code without setting up and managing servers. The code is automatically invoked based on variou triggers that can be setup.

2) Severless Web apps can use Lambdas that respond to user request. Real-time data processing can happen. Data ETL can happen with Lambdas before the data reaches a warehouse.

3) "Serverless" is a new way of building and running applications that allows developers to focus on writing code, without worrying about servers. With AWS Lambda, for example, developers can simply write their code, upload it to the cloud, and let AWS Lambda handle the rest. AWS Lambda automatically manages the servers, runs the code in response to events, and scales up or down based on demand.le.

CDN

1) Content Delivery Network is a distributed network of servers located in various geographical locations, designed to deliver content, such as images, videos, web pages, and other media, to users around the world.

2) The request is routed to the nearest server in the CDN. The CDN server then sees if it has a cached copy of the requested content to send back as as response.

3) Faster content delivery and increased reliability (due to its redunancy of multiple servers in the region).