# Spring Boot Learning Resources

A curated collection of high-quality, free resources to accompany the
Spring Boot roadmap.

> **Target Stack**
>
> -   Java 21+
> -   Spring Framework 6.x
> -   Spring Boot 3.x
> -   Maven 3.9+ / Gradle 8+
> -   PostgreSQL 16+

This document prioritizes **official documentation first**, followed by
carefully selected community resources and a single recommended video
where appropriate.

------------------------------------------------------------------------

## Java Fundamentals

### Official Documentation

-   [Java Documentation](https://docs.oracle.com/en/java/)
-   [Inside Java](https://inside.java/)

### Recommended Reading

-   Modern Java Language Features
-   Virtual Threads
-   Records
-   Sealed Classes
-   Streams API
-   CompletableFuture
-   Executor Framework

### Videos

-   Java Programming -- freeCodeCamp

------------------------------------------------------------------------

## Build Tools

### Official Documentation

-   Apache Maven
-   Gradle User Guide

### Recommended Reading

-   Maven Fundamentals
-   Gradle Fundamentals
-   Maven vs Gradle

------------------------------------------------------------------------

## Spring Framework

### Official Documentation

-   Spring Framework Reference

### Recommended Reading

-   IoC & Dependency Injection
-   Bean Lifecycle
-   Bean Scopes
-   Spring AOP
-   Application Events

------------------------------------------------------------------------

## Spring Boot

### Official Documentation

-   Spring Boot Reference
-   Spring Guides
-   Spring Academy
-   Spring Initializr

### Recommended Reading

-   Auto Configuration
-   Configuration Properties
-   Profiles
-   Actuator
-   DevTools

### Video

-   Spring Boot Crash Course (Amigoscode)

------------------------------------------------------------------------

## Configuration

-   External Configuration
-   Profiles
-   Configuration Properties
-   Environment Variables
-   Secrets Management

------------------------------------------------------------------------

## Validation

-   Jakarta Bean Validation
-   Custom Validators
-   Method Validation

------------------------------------------------------------------------

## REST APIs

### Official Documentation

-   Building a REST Service

### Recommended Reading

-   REST Best Practices
-   Exception Handling
-   Problem Details (RFC 7807)
-   Pagination
-   Rate Limiting (Bucket4j)

------------------------------------------------------------------------

## API Documentation

-   SpringDoc OpenAPI
-   Swagger UI
-   Spring REST Docs

------------------------------------------------------------------------

## Persistence

### Official Documentation

-   Spring Data JPA

### Recommended Reading

-   Entity Mapping
-   Relationships
-   Transactions
-   Specifications
-   Auditing
-   Flyway
-   Liquibase
-   Testcontainers

------------------------------------------------------------------------

## Databases

-   PostgreSQL
-   Redis

------------------------------------------------------------------------

## Security

### Official Documentation

-   Spring Security Reference
-   Spring Authorization Server

### Recommended Reading

-   Authentication
-   Authorization
-   JWT
-   OAuth2 Resource Server
-   Method Security

------------------------------------------------------------------------

## API Clients

### Official Documentation

-   RestClient
-   WebClient

> Prefer **RestClient** for synchronous HTTP calls and **WebClient** for
> reactive applications. `RestTemplate` is maintained for legacy
> applications.

------------------------------------------------------------------------

## Caching

-   Spring Cache
-   Redis Cache

------------------------------------------------------------------------

## Scheduling

-   @Scheduled
-   Quartz Scheduler

------------------------------------------------------------------------

## Testing

### Official Documentation

-   Spring Boot Testing

### Recommended Reading

-   JUnit 5
-   Mockito
-   MockMvc
-   WebTestClient
-   Testcontainers
-   AssertJ

------------------------------------------------------------------------

## Logging

-   SLF4J
-   Logback
-   Structured Logging

------------------------------------------------------------------------

## Messaging

-   RabbitMQ
-   Apache Kafka

------------------------------------------------------------------------

## Monitoring & Observability

-   Spring Boot Actuator
-   Micrometer
-   Prometheus
-   Grafana
-   OpenTelemetry

------------------------------------------------------------------------

## Docker

-   Docker Documentation
-   Dockerizing Spring Boot
-   Buildpacks
-   Docker Compose Support

------------------------------------------------------------------------

## CI/CD

-   GitHub Actions
-   Maven/Gradle Build Pipelines

------------------------------------------------------------------------

## Cloud & Deployment

-   Spring Cloud
-   Spring Cloud Gateway
-   Spring Cloud Config
-   Kubernetes
-   AWS
-   Azure
-   Google Cloud

------------------------------------------------------------------------

## Architecture & Design

-   Layered Architecture
-   Clean Architecture
-   Hexagonal Architecture
-   Domain-Driven Design
-   SOLID Principles

------------------------------------------------------------------------

## Advanced Spring

-   Spring Modulith
-   Spring AI
-   Reactive Programming (WebFlux)
-   Native Images (GraalVM)
-   GraphQL
-   Resilience4j
-   Spring Retry
-   Microservices

------------------------------------------------------------------------

## Additional References

-   roadmap.sh Spring Boot
-   Spring Projects
-   Spring GitHub Organization
-   Awesome Spring Boot

------------------------------------------------------------------------

## Notes

-   Prefer official Spring documentation whenever available.
-   Community resources such as Baeldung are excellent supplements, not
    replacements.
-   Keep dependencies aligned with the latest Spring Boot 3.x release.
-   Use Java 21 LTS for all new projects.
