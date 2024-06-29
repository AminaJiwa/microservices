# Spring Boot 

This is a Java/ Spring Boot e-commerce application created using a microservices architecture. It utilises Spring Cloud for its cloud-native support which allows for a robust and scalable system. I created integration tests using Test Containers allowing simulation of real-world scenarios and validation of service interactions in an isolated environment. The system consists of three core services: Product, Inventory, and Order. The Product Service manages the product catalogue, the Inventory Service oversees stock levels, and the Order Service handles the purchasing process. The Notification Service allows users to be notified when an order is placed using Kafka. An API gateway is also included, which acts as the single entry point for all client requests. It routes requests to the appropriate microservice, whether it’s Product, Inventory, or Order, and also provides an additional layer of security and load balancing.  

Product service: https://github.com/AminaJiwa/microservices-java-product  
Inventory service: https://github.com/AminaJiwa/microservices-java-inventory  
Order service: https://github.com/AminaJiwa/microservices-java-order  
Notification service: https://github.com/AminaJiwa/microservices-notification  
API gateway: https://github.com/AminaJiwa/microservices-api-gateway  
