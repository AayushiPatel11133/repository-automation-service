# Repository Automation Service

A Spring Boot demonstration project that showcases repository and deployment automation concepts using a clean service architecture, external API integration, validation, configuration management, and automated testing.

This project is built as a portfolio-safe recreation of repository automation patterns I have worked with professionally. It does not contain proprietary employer source code, internal URLs, credentials, client information, or confidential business logic.

## Tech Stack

- Java 17
- Spring Boot
- Spring WebFlux
- WebClient
- Bean Validation
- Lombok
- Maven
- JUnit 5
- Mockito
- Docker
- GitHub Actions

## Planned Features

The first version of the service will support:

- Create repository
- Retrieve repository details
- Enable pipeline configuration
- Create deployment environments
- Add repository-level variables
- Add environment-level variables
- Orchestrate repository setup through a single automation workflow

## Project Structure

```text
src/main/java/com/aayushipatel/repositoryautomation

├── client
├── config
├── controller
├── dto
├── exception
└── service