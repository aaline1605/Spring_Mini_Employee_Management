Spring_Mini_Employee_Management

Welcome to the Employee Management System! This project is designed to help you manage employee details efficiently using Spring Boot, Thymeleaf, and MongoDB. It includes features like
adding new employees, updating existing employee information, deleting employees, and searching for employees by their ID. To see this project output as video,Screenshots, and documentation.
I attached Drive Link above Acknowledgement section.

## Table of Contents
- Introduction
- Features
- Technologies Used
- Prerequisites
- Installation
- Usage
- FrontEnd
- Acknowledgements

## Introduction
The Employee Management System is a web application that provides an interface to manage employee data. It uses Spring Boot for the backend, Thymeleaf for the frontend, and MongoDB as the database.

## Features
- **Add Employee**: Register a new employee with details like Employee ID, Name, Email, Job Location, Department, and Address.
- **View Employees**: Display all registered employees in a tabular format.
- **Update Employee**: Edit existing employee details.
- **Delete Employee**: Remove an employee from the system.
- **Search Employee**: Find employees by their Employee ID.

## Technologies Used
- ***Spring Boot***: For creating the backend REST APIs.
- ***Thymeleaf***: For rendering the frontend views.
- ***MongoDB***: As the database to store employee data.
- ***Maven***: For project management and dependencies.
- ***Lombok***: To reduce boilerplate code.

## Prerequisites
- Java 17
- Maven
- MongoDB Atlas (or local MongoDB instance)

## Installation
1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/employee-management-system.git
    cd employee-management-system
    ```

2. **Configure MongoDB**:
    Update the MongoDB URI in `application.yml`:
    ```yaml
    spring:
      data:
        mongodb:
          uri: "your-mongodb-uri"
    ```

3. **Build and Run the application**:
    ```bash
    mvn clean install
    mvn spring-boot:run
    ```

## Usage
- **Access the application**: Open your browser and go to `http://localhost:8080`.
- **Home Page**: You will see options to add staff, display staff details, and search for staff by ID.
- **Add Staff**: Fill in the form to register a new employee.
- **Display Staff Details**: View the list of all employees with options to update or delete each entry.
- **Search**: Enter an Employee ID to find specific employee details.

## FrontEnd 
- To see FrontEnd part as well as Screenshots and Documentation you can use Drive link here...,
- Click here: https://drive.google.com/drive/folders/1Dwwwx3SSL3FYp6hpdtWa9IIpiOv-Tbwm?usp=drive_link

## Acknowledgements
- Special thanks to the Spring Boot, Thymeleaf, and MongoDB communities for their excellent documentation and support.

**Discover the Best in Quality and Assurance with AR Products.**

---

*Happy Coding!*

