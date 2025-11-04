# microservices-config

This repository contains centralized configuration files for microservices to be served by Spring Cloud Config Server.

Included files:
- `application.properties`: Common settings applied to all services.
- `application-prod.properties`: Common production settings (Actuator scope, tracing probability, Eureka).
- `api-gateway.properties`: API Gateway configuration.
- `authorization-service.properties`: Authorization service configuration.
- `product-service.properties`: Product service configuration.
- `review-service.properties`: Review service configuration.
- `recommendation-service.properties`: Recommendation service configuration.
- `product-composite-service.properties`: Product composite service configuration.

Production profile files (activated with `--spring.profiles.active=prod`):
- `authorization-service-prod.properties`: MySQL, JPA, and prod port for the authorization service.
- `product-service-prod.properties`: MySQL, JPA, and prod port for the product service.
- `review-service-prod.properties`: MySQL, JPA, and prod port for the review service.
- `recommendation-service-prod.properties`: MySQL, JPA, and prod port for the recommendation service.
- `product-composite-service-prod.properties`: MySQL, JPA, and prod port for the composite service.
