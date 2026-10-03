# Journal Management Application

A backend application built using **Java and Spring Boot** to manage personal journal entries through RESTful APIs. The project uses Spring MVC to handle HTTP requests and provides a structured foundation for journal-related operations.

## Tech Stack

- **Language:** Java 17
- **Framework:** Spring Boot
- **Web:** Spring MVC
- **Build Tool:** Maven
- **API:** REST

## Features

- RESTful API architecture for journal management
- HTTP request handling using Spring MVC
- Structured backend development using Spring Boot

## Project Structure

```text
journalApp/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/chinmai/
│   │   └── resources/
│   └── test/
├── .gitignore
├── mvnw
├── mvnw.cmd
├── pom.xml
└── README.md
```

## Getting Started

### Prerequisites

- Java 17 or later
- Maven
- Git

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/chiy4you-real/journalApp.git
   ```

2. Navigate to the project directory:

   ```bash
   cd journalApp
   ```

3. Run the application using Maven:

   ```bash
   ./mvnw spring-boot:run
   ```

   On Windows:

   ```bash
   mvnw.cmd spring-boot:run
   ```

4. The application will start on the default Spring Boot port, `8080`, unless configured otherwise.

## Learning Objectives

- Understanding backend application architecture
- Building RESTful APIs using Spring Boot
- Handling HTTP requests using Spring MVC
- Managing dependencies and builds using Maven

## Future Improvements

- Integrate a relational database for persistent journal storage
- Implement user authentication and authorization
- Add input validation and exception handling
- Develop a frontend for interacting with journal entries

## Author

**Chinmai Patil**

[GitHub](https://github.com/chiy4you-real)
