
# Spring CRUD Application with H2 Database

This project is a simple Spring Boot application demonstrating CRUD operations using Spring Data JPA and an H2 in-memory database. The application provides RESTful APIs to create, retrieve, update, and delete entities.

## Features

- Perform CRUD operations on an entity
- In-memory database (H2) for easy setup and testing
- RESTful API with standard HTTP methods
- Easy to use and configure

## Technologies Used

- Spring Boot
- Spring Data JPA
- H2 Database
- Maven

## Getting Started

### Prerequisites

- Java 8 or higher
- Maven

### Installation

1. Clone the repository:
   ```bash
   https://github.com/AkashGodase/Spring-Boot-CRUD-Application.git
   ```
2. Navigate to the project directory:
   ```bash
   cd repository-name
   ```
3. Install the dependencies:
   ```bash
   mvn clean install
   ```
4. Run the application:
   ```bash
   mvn spring-boot:run
   ```

## Usage

Once the application is running, you can access the API endpoints at `http://localhost:8080/api`.

Replace `Employee`,`Address` with the actual entity name used in your project.

## Database

The application uses an in-memory H2 database. You can access the H2 console at `http://localhost:8080/h2-console` with the following details:

- **JDBC URL**: `jdbc:h2:mem:jdbc`
- **Username**: `root`
- **Password**: `root`

## Contributing

If you would like to contribute, please fork the repository and create a pull request. For major changes, please open an issue first to discuss your ideas.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
