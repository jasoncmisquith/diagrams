[eraser.io/diagramgpt
](https://www.eraser.io/diagramgpt)```
Cloud architecture for 3 different services
Service 1 is a API service built with kubernetes microservices hosted on AWS EC2 served to client using the AWS Api Gateway, Service 1 has a Postgres database and AWS Elasticache. All requests for the API request from AWS API Gateway are authorized by authorizer lambda and rerouted using the interceptor lambda.
The kubernetes services include NestJS controllers which forward request to nestJS Service pods.
There are 3 types of nestjs controllers and its corresponding services. Account, BGT```
