# Contact Management System

A Java-based Contact Management System that allows users to store and manage their contacts efficiently. The system uses MySQL for data storage and provides a simple interface for managing contact information.

## Features

- Add new contacts
- View existing contacts
- Update contact information
- Delete contacts
- Search for contacts

## Prerequisites

- Java JDK 8 or higher
- MySQL Server
- MySQL Workbench (optional, for database management)

## Database Setup

1. Create a new MySQL database named `contact_manager`
2. The application will automatically handle table creation
3. Update the database configuration in `src/main/java/com/contactmanager/dao/DatabaseConfig.java` if needed

## Building the Project

This project uses Maven for dependency management. To build the project:

```bash
mvn clean install
```

## Running the Application

After building, you can run the application using:

```bash
java -jar target/contactmanager.jar
```

## Configuration

Database configuration can be found in `src/main/java/com/contactmanager/dao/DatabaseConfig.java`. Update the following properties as needed:

- `URL`: JDBC connection URL
- `USER`: Database username
- `PASSWORD`: Database password
