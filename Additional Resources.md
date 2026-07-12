# Spring Boot Learning Resources

A curated collection of free, high-quality resources to accompany the Spring Boot Roadmap.

This document prioritizes official documentation wherever possible. Community articles and videos are included as supplementary resources.

## Target Stack

* Java 21+
* Spring Framework 6.x
* Spring Boot 3.x
* Maven 3.9+ / Gradle 8+
* PostgreSQL 16+

---

## Java Fundamentals

### Official Documentation

* [Java Documentation][java-docs]

### Recommended Reading

* [Modern Java Features][modern-java]
* [Virtual Threads][virtual-threads]
* [Java Records][java-records]
* [Sealed Classes][sealed-classes]
* [Streams API][streams]
* [CompletableFuture][completablefuture]
* [Executor Service][executor-service]

### Video

* [Java Programming Course (freeCodeCamp)][java-video]

---

## Build Tools

### Official Documentation

* [Apache Maven][maven-docs]
* [Gradle User Guide][gradle-docs]

### Recommended Reading

* [Maven][maven]
* [Gradle][gradle]
* [Maven vs Gradle][maven-gradle]

---

## Spring Framework

### Official Documentation

* [Spring Framework Reference][spring-framework]

### Recommended Reading

* [Dependency Injection][dependency-injection]
* [Spring Beans][spring-beans]
* [Bean Scopes][bean-scopes]
* [Bean Lifecycle][bean-lifecycle]
* [Spring AOP][spring-aop]
* [Application Events][application-events]

---

## Spring Boot

### Official Documentation

* [Spring Boot Reference][spring-boot]
* [Spring Guides][spring-guides]
* [Spring Initializr][spring-initializr]

### Recommended Reading

* [Configuration Properties][configuration-properties]
* [Spring Profiles][spring-profiles]
* [Spring Boot Actuator][actuator]
* [Auto Configuration][auto-configuration]

### Video

* [Spring Boot Crash Course (Amigoscode)][spring-boot-video]

---

## Configuration

### Official Documentation

* [External Configuration][external-config]

### Recommended Reading

* [Configuration Properties][configuration-properties]
* [Profiles][spring-profiles]
* [@Value Annotation][value-annotation]

---

## Validation

### Official Documentation

* [Jakarta Bean Validation][bean-validation]

### Recommended Reading

* [Bean Validation with Spring Boot][spring-validation]
* [Custom Validators][custom-validation]

---

## Building REST APIs

### Official Documentation

* [Building a REST Service][rest-guide]

### Recommended Reading

* [REST API with Spring Boot][rest-api]
* [Exception Handling][exception-handling]
* [Rate Limiting with Bucket4j][bucket4j]
* [REST API Design Guidelines][rest-guidelines]

---

## API Documentation

### Official Documentation

* [SpringDoc OpenAPI][springdoc]

### Recommended Reading

* [OpenAPI with Spring Boot][openapi]

---

## Persistence

### Official Documentation

* [Spring Data JPA][spring-data-jpa]

### Recommended Reading

* [Spring Data JPA Guide][jpa-guide]
* [Entity Relationships][entity-relationships]
* [Transactions][transactions]
* [Specifications][specifications]
* [Flyway Database Migrations][flyway]
* [Testcontainers][testcontainers]

---

## Databases

### Official Documentation

* [PostgreSQL Documentation][postgres-docs]
* [Redis Documentation][redis-docs]

### Recommended Reading

* [Spring Boot with PostgreSQL][postgres]
* [Spring Data Redis][redis]

---

## Security

### Official Documentation

* [Spring Security Reference][spring-security]

### Recommended Reading

* [Spring Security Basics][security]
* [JWT Authentication][jwt]
* [OAuth2 Resource Server][oauth2]
* [Database Authentication][database-auth]

---

## API Clients

### Official Documentation

* [WebClient][webclient-docs]

### Recommended Reading

* [WebClient Guide][webclient]

> `WebClient` is the recommended HTTP client for modern Spring applications. `RestTemplate` is maintained for legacy applications.

---

## Caching

### Recommended Reading

* [Spring Cache][cache]
* [Redis Caching][redis]

---

## Scheduling

### Official Documentation

* [Task Execution and Scheduling][scheduling-docs]

### Recommended Reading

* [Spring Scheduling][scheduling]
* [Quartz Scheduler][quartz]

---

## Testing

### Official Documentation

* [Spring Boot Testing][testing-docs]

### Recommended Reading

* [Spring Boot Testing][testing]
* [Mockito][mockito]
* [WebTestClient][webtestclient]
* [Testcontainers][testcontainers]

---

## Logging

### Recommended Reading

* [Spring Boot Logging][logging]
* [SLF4J and Logback][slf4j]

---

## Deployment

### Official Documentation

* [Docker Documentation][docker-docs]
* [GitHub Actions Documentation][github-actions]

### Recommended Reading

* [Dockerizing Spring Boot][docker]
* [Spring Boot Container Images][container-images]

---

## Monitoring & Observability

### Official Documentation

* [OpenTelemetry][opentelemetry]
* [Prometheus][prometheus]
* [Grafana][grafana]

### Recommended Reading

* [Micrometer][micrometer]
* [Spring Boot Actuator][actuator]

---

## Cloud

### Official Documentation

* [Spring Cloud][spring-cloud]
* [Kubernetes Documentation][kubernetes]

### Recommended Reading

* [Spring Cloud Function][cloud-function]

---

## Messaging

### RabbitMQ

* [Spring AMQP][rabbitmq]

### Apache Kafka

* [Confluent Spring for Apache Kafka][kafka]

---

## Reactive Programming

### Official Documentation

* [Spring WebFlux][webflux-docs]

### Recommended Reading

* [Spring WebFlux Guide][webflux]

---

## GraphQL

### Official Documentation

* [Spring for GraphQL][spring-graphql]

### Recommended Reading

* [GraphQL with Spring Boot][graphql]

---

## Microservices

### Official Documentation

* [Spring Cloud][spring-cloud]

### Video

* [Microservices with Spring Boot][microservices-video]

---

## Authentication & Identity

### Official Documentation

* [Keycloak Documentation][keycloak-docs]

### Recommended Reading

* [Keycloak with Spring Boot][keycloak]

---

## Architecture & Design

### Recommended Reading

* [Clean Architecture with Spring Boot][clean-architecture]
* [Hexagonal Architecture][hexagonal]
* [Domain-Driven Design Overview][ddd]

---

## Additional References

* [Spring Projects][spring-projects]
* [Roadmap.sh – Spring Boot][roadmap]
* [Awesome Spring Boot][awesome-springboot]
* [Spring GitHub Organization][spring-github]

---

## References

[java-docs]: https://docs.oracle.com/en/java/
[java-video]: https://www.youtube.com/watch?v=GoXwIVyNvX0
[modern-java]: https://dev.to/codeshakes/modern-java-features-from-java-8-to-java-17-5ehe
[virtual-threads]: https://www.baeldung.com/java-virtual-threads
[java-records]: https://www.baeldung.com/java-record-keyword
[sealed-classes]: https://www.baeldung.com/java-sealed-classes
[streams]: https://www.baeldung.com/java-streams
[completablefuture]: https://www.baeldung.com/java-completablefuture
[executor-service]: https://www.baeldung.com/java-executor-service-tutorial
[maven-docs]: https://maven.apache.org/guides/
[gradle-docs]: https://docs.gradle.org/current/userguide/
[maven]: https://www.baeldung.com/maven
[gradle]: https://www.baeldung.com/gradle
[maven-gradle]: https://www.baeldung.com/maven-vs-gradle
[spring-framework]: https://docs.spring.io/spring-framework/reference/
[dependency-injection]: https://www.baeldung.com/inversion-control-and-dependency-injection-in-spring
[spring-beans]: https://www.baeldung.com/spring-bean
[bean-scopes]: https://www.baeldung.com/spring-bean-scopes
[bean-lifecycle]: https://www.baeldung.com/spring-bean-life-cycle
[spring-aop]: https://www.baeldung.com/spring-aop
[application-events]: https://www.baeldung.com/spring-events
[spring-boot]: https://docs.spring.io/spring-boot/reference/
[spring-guides]: https://spring.io/guides
[spring-initializr]: https://start.spring.io/
[spring-boot-video]: https://www.youtube.com/watch?v=9SGDpanrc8U
[configuration-properties]: https://www.baeldung.com/configuration-properties-in-spring-boot
[spring-profiles]: https://www.baeldung.com/spring-profiles
[actuator]: https://www.baeldung.com/spring-boot-actuators
[auto-configuration]: https://docs.spring.io/spring-boot/reference/using/auto-configuration.html
[external-config]: https://docs.spring.io/spring-boot/reference/features/external-config.html
[value-annotation]: https://www.baeldung.com/spring-value-annotation
[bean-validation]: https://beanvalidation.org/
[spring-validation]: https://www.baeldung.com/spring-boot-bean-validation
[custom-validation]: https://www.baeldung.com/spring-mvc-custom-validator
[rest-guide]: https://spring.io/guides/gs/rest-service/
[rest-api]: https://www.baeldung.com/building-a-restful-web-service-with-spring-and-java-based-configuration
[exception-handling]: https://www.baeldung.com/exception-handling-for-rest-with-spring
[bucket4j]: https://www.baeldung.com/spring-bucket4j
[rest-guidelines]: https://learn.microsoft.com/azure/architecture/best-practices/api-design
[springdoc]: https://springdoc.org/
[openapi]: https://www.baeldung.com/spring-rest-openapi-documentation
[spring-data-jpa]: https://spring.io/projects/spring-data-jpa
[jpa-guide]: https://www.baeldung.com/the-persistence-layer-with-spring-data-jpa
[entity-relationships]: https://www.baeldung.com/jpa-join-types
[transactions]: https://www.baeldung.com/spring-transactional-propagation-isolation
[specifications]: https://www.baeldung.com/rest-api-search-language-spring-data-specifications
[flyway]: https://www.baeldung.com/database-migrations-with-flyway
[testcontainers]: https://www.testcontainers.org/
[postgres-docs]: https://www.postgresql.org/docs/
[redis-docs]: https://redis.io/docs/
[postgres]: https://www.callicoder.com/spring-boot-jpa-hibernate-postgresql-restful-crud-api-example/
[redis]: https://www.baeldung.com/spring-data-redis-tutorial
[spring-security]: https://docs.spring.io/spring-security/reference/
[security]: https://www.baeldung.com/security-spring
[jwt]: https://www.baeldung.com/spring-security-oauth-jwt
[oauth2]: https://www.baeldung.com/spring-security-oauth-resource-server
[database-auth]: https://www.baeldung.com/spring-security-authentication-with-a-database
[webclient-docs]: https://docs.spring.io/spring-framework/reference/web/webflux-webclient.html
[webclient]: https://www.baeldung.com/spring-webclient-resttemplate
[cache]: https://www.baeldung.com/spring-cache-tutorial
[scheduling-docs]: https://docs.spring.io/spring-framework/reference/integration/scheduling.html
[scheduling]: https://www.baeldung.com/spring-scheduled-tasks
[quartz]: https://www.quartz-scheduler.org/documentation/
[testing-docs]: https://docs.spring.io/spring-boot/reference/testing/
[testing]: https://www.baeldung.com/spring-boot-testing
[mockito]: https://www.baeldung.com/mockito-series
[webtestclient]: https://www.baeldung.com/spring-web-testclient
[logging]: https://www.baeldung.com/spring-boot-logging
[slf4j]: https://www.baeldung.com/slf4j-with-log4j2-logback
[docker-docs]: https://docs.docker.com/
[docker]: https://www.baeldung.com/dockerizing-spring-boot-application
[container-images]: https://docs.spring.io/spring-boot/reference/packaging/container-images/
[github-actions]: https://docs.github.com/actions
[opentelemetry]: https://opentelemetry.io/docs/
[prometheus]: https://prometheus.io/docs/
[grafana]: https://grafana.com/docs/
[micrometer]: https://www.baeldung.com/micrometer
[spring-cloud]: https://spring.io/projects/spring-cloud
[kubernetes]: https://kubernetes.io/docs/
[cloud-function]: https://www.baeldung.com/spring-cloud-function
[rabbitmq]: https://www.baeldung.com/spring-amqp
[kafka]: https://developer.confluent.io/courses/spring/
[webflux-docs]: https://docs.spring.io/spring-framework/reference/web/webflux.html
[webflux]: https://www.baeldung.com/spring-webflux
[spring-graphql]: https://spring.io/projects/spring-graphql
[graphql]: https://www.baeldung.com/spring-graphql
[microservices-video]: https://www.youtube.com/watch?v=mlbOZXpZ-FY
[keycloak-docs]: https://www.keycloak.org/guides
[keycloak]: https://www.baeldung.com/spring-boot-keycloak
[clean-architecture]: https://www.baeldung.com/spring-boot-clean-architecture
[hexagonal]: https://www.baeldung.com/hexagonal-architecture-ddd-spring
[ddd]: https://martinfowler.com/tags/domain%20driven%20design.html
[spring-projects]: https://spring.io/projects
[roadmap]: https://roadmap.sh/spring-boot
[awesome-springboot]: https://github.com/CodepediaOrg/awesome-springboot
[spring-github]: https://github.com/spring-projects
