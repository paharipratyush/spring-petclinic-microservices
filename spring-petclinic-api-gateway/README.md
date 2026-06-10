# Spring Petclinic API Gateway

API gateway and frontend for the Spring Petclinic microservices platform.

Runs on port `8080`. Routes all inbound traffic to downstream services via Spring Cloud Gateway.
Built with Spring Boot 4.0.6 and deployed to ARM64 (Graviton) EKS nodes.
Uses Netty (reactive) — no Tomcat dependency.
