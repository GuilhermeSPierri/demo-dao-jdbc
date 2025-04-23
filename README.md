# JDBC DAO Demo Project

This is a simple Java project demonstrating the implementation of CRUD operations (Create, Read, Update, and Delete) using JDBC with a MySQL database.

The project follows the DAO (Data Access Object) design pattern to organize data access logic in a clean and modular way.

## 🛠️ Technologies Used

- Java
- JDBC
- MySQL

## 🚀 Features
- Insert, update, delete, and find operations for `Seller` and `Department` entities
- Database connection management
- Modular and organized code structure using interfaces and implementation classes

## 📁 Project Structure

- `src/db`: Handles database connection and error handling
- `src/model/entities`: Contains the entity classes
- `src/model/dao`: Interfaces for data access
- `src/model/dao/impl`: DAO implementations
- `src/application`: Contains the main class for testing features

## 💡 Getting Started

To run this project:

1. Set up a MySQL database using the `database.sql` script.
2. Configure your database credentials in `db.properties`.
3. Compile and run the project using your preferred IDE.

## 📌 Note

This project is for educational purposes, based on a course from Udemy.
