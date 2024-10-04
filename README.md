# CSCI 366: JDBC Lab

## Overview
This project is a Java application that allows users to create, view, edit, and delete student records using a relational database (PostgreSQL) and CSV file storage. It follows the Model-View-Controller (MVC) design pattern to separate concerns and enhance maintainability.

## Objectives
- Write Java applications that interact with relational databases.
- Implement CRUD (Create, Read, Update, Delete) operations for student records.
- Utilize the MVC design pattern to structure the application.

## Setup Instructions

### Database Setup
1. Connect to the PostgreSQL database named `a07students_yourname` (replace `yourname` with your username).
2. Execute the SQL scripts in the following order:
   - `/home/faculty/chogg/Public/366/a07students/DDL.sql`
   - `/home/faculty/chogg/Public/366/a07students/smallRelationsInsertFile.sql`
3. Set a password for your database account using the command:

### Development Environment
1. Use Eclipse IDE for Java Developers for development.
2. Download the latest PostgreSQL JDBC driver from [PostgreSQL JDBC Download](https://jdbc.postgresql.org/download/).
3. Create a `lib` folder in your Eclipse project and add the JDBC driver there.
4. Ensure that the driver is included in your Java Build Path.

### Project Structure

## Usage
1. Run the `Lab07Main` class to start the application.
2. Choose whether to use the PostgreSQL database or the CSV file for storing student records.
3. Select between a graphical (Swing) or console interface for user interaction.

### Features
- **CRUD Operations**: Create, Read, Update, and Delete student records.
- **Data Sources**: Supports both PostgreSQL database and CSV file storage.
- **User Interface**: Provides both a Swing GUI and a console-based interface for user interaction.

## Requirements
- Java Development Kit (JDK) 8 or higher.
- PostgreSQL database.
- Eclipse IDE for Java Developers.

## Contributions
This project was developed as part of the CSCI 366 course at Millersville University.

## License
This project is licensed under the MIT License - see the [MIT LICENSE](LICENSE) file for details.
