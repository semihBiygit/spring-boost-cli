# SpringBoost CLI - Boost Your Spring Projects

SpringBoost CLI is a powerful command-line tool designed to accelerate the process of setting up Spring Boot projects. With just a few commands, you can generate the fundamental structure and boilerplate code for your Spring applications.

## Features

- Quickly generate the base code for your Spring Boot projects.
- Easily configure database settings for MySQL, H2, PostgreSQL, and MSSQL.
- Efficiently create models, repositories, services, and controllers with just one command.
- Seamless integration with popular Java build tool Maven.
- User-friendly command-line interface using the Picocli library.

## Getting Started

1. **Clone the Repository**: First, clone this repository to your local machine using the following command:

    ```sh
    git clone https://github.com/semihBiygit/spring-boost-cli.git
    ```

2. **Navigate to the Project Directory**: Change into the project directory:

    ```sh
    cd spring-boost-cli
    ```

3. **Build the Project**: Use Maven to build the project and create the executable JAR file:

    ```sh
    mvn package
    ```

4. **Run the CLI**: Now, you can run the SpringBoost CLI using the following command:

    ```sh
    java -jar target/SpringBoost-0.0.1.jar
    ```

5. **Follow the Prompts**: The CLI will guide you through generating your Spring Boot project. Provide the project name, package name, and select the database type when prompted.

6. **Generated Project**: After the process completes, a new directory with your specified project name will be created, containing the generated Spring Boot project files.

## Supported Database Types

- MySQL
- H2
- PostgreSQL
- MSSQL

## Example Usage

Generate a Spring Boot project with MySQL database configuration:

```sh
java -jar target/SpringBoost-0.0.1.jar --projectName=myProject --packageName=com.example --dbType=mysql
```

## Dependencies

- Spring Boot: 2.4.2
- Spring Boot Starter Data JPA
- Spring Boot Starter Web
- Other dependencies based on the selected database type.

## Contributing

Contributions are welcome! If you encounter any issues or have suggestions for improvements, please [open an issue](https://github.com/semihBiygit/spring-boost-cli/issues) or [submit a pull request](https://github.com/semihBiygit/spring-boost-cli/pulls).

