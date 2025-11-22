# E-commerce Microservices Backend
Implemented backend system of an e-commerce application built in micro-service pattern

This project implements a fully containerized, event-driven e-commerce backend following a microservices architecture. Each business capability—such as products, orders, payments, emails, authentication, and routing—is implemented as a dedicated Spring Boot microservice, communicating through REST and Apache Kafka.

An API Gateway provides a single unified entry point, while a Eureka Server manages dynamic service discovery. Each service maintains its own MySQL database, ensuring data isolation and independent scalability. Redis is used for caching and fast session/token handling, and Zipkin offers end-to-end distributed tracing across services. Docker and Docker Compose orchestrate the entire ecosystem, enabling seamless multi-service deployment, networking, and environment consistency.

The architecture focuses on modularity, loose coupling, observability, and resilience—making it suitable for learning, experimentation, and building production-grade distributed systems.
