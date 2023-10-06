# Doner Cloud

[![Build Status](https://travis-ci.com/username/repo.svg?branch=main)](https://travis-ci.com/username/repo)

## Introduction

Doner Cloud is a Java Spring project that provides a cloud-based platform for managing and ordering delicious doners.

## Features

- User registration and authentication
- Menu management
- Doner ordering and tracking
- Payment integration
- Delivery tracking

## Technologies Used

- Java
- Spring Boot
- Spring MVC
- Spring Data JPA
- Thymeleaf
- PostgreSQL
- Gradle (as the build tool)

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 21 or higher
- PostgreSQL
- Gradle (as the build tool)

### Installation

1. Clone the repository:

   ```shell
   git clone https://github.com/username/repo.git
   ```

2. Configure the database connection in the `application.properties` file:

   ````properties
   spring.datasource.url=jdbc:postgresql://${db_host}:${db_port}/${repo_name}
   spring.datasource.username=${username}
   spring.datasource.password=${password}
   ```

3. Build the project:

   ````shell
   ./gradlew build
   ```

4. Run the application:

   ````shell
   ./gradlew bootRun
   ```

## Usage

- Access the application at: `http://localhost:8080`
- Follow the provided documentation and user guides to use the different features of the Doner Cloud platform.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request.

## Acknowledgements

- [Spring Framework](https://spring.io/)
- [Thymeleaf](https://www.thymeleaf.org/)
- [PostgreSQL](https://www.postgresql.org/)
- [Gradle](https://gradle.org/)
