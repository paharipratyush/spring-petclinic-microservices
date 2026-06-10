# Spring Petclinic Customers Service

Manages owner and pet data for the Spring Petclinic microservices platform.

Runs on port `8081`. Requires MySQL (RDS). Registers with Eureka for service discovery.
Built with Spring Boot 4.0.6 and deployed to ARM64 (Graviton) EKS nodes.
Stores owner profiles, pet records, and species/breed metadata.
