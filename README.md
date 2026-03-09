# Flexi ATM System

## Overview

Flexi ATM is a Java-based software application that simulates the core functionality of an Automated Teller Machine (ATM).
The system allows users to perform fundamental banking operations such as checking account balance, withdrawing funds, depositing money, and receiving transaction notifications.

The project was developed as an academic software project in order to demonstrate the application of Object-Oriented Programming principles, graphical user interface development, and modular system architecture.

The system is designed to mimic real ATM workflows while maintaining a clear and maintainable program structure.

---

## System Features

### User Interaction

The system provides a structured interface that enables users to interact with the ATM services in an organized and intuitive manner.

### Balance Inquiry

Users can view their current account balance at any time through the system interface.

### Withdrawal Operations

The application allows users to withdraw funds from their account while verifying that sufficient balance is available.

### Deposit Operations

Users may deposit funds into their account, and the system updates the account balance accordingly.

### Email Notification Service

The system supports email notifications that inform users when important financial transactions such as withdrawals or deposits are completed.

### Transaction Processing

All financial operations are handled through a dedicated transaction management process that ensures consistency and accuracy in balance updates.

### Input Validation

The system includes validation mechanisms to prevent invalid actions such as negative transaction amounts or withdrawals exceeding the available balance.

### Graphical User Interface

The application includes a graphical interface implemented using Java Swing in order to provide a more accessible and user-friendly interaction environment.

### Modular System Design

The project follows a modular architecture where responsibilities are separated across multiple packages to improve maintainability, scalability, and readability.

---

## Technologies Used

* Java
* Java Swing (Graphical User Interface)
* Object-Oriented Programming (OOP)
* Email Service Integration
* Data Management Components

---

## Project Structure

The project is organized into several packages, each responsible for a specific part of the system.

**src/DataBase**
Handles the storage and retrieval of account-related data.

**src/Emails**
Responsible for sending transaction-related email notifications.

**src/Features**
Contains the implementation of the core ATM operations such as withdrawal, deposit, and balance inquiry.

**src/GUIjavaSwing**
Implements the graphical user interface of the system using Java Swing.

**src/Main**
Manages the main execution flow of the application.

**src/Management**
Coordinates communication between system components and manages application logic.

**src/assets**
Stores supporting resources used by the application.

**App.java**
Serves as the entry point of the application and initializes the system.

---

## Installation and Execution

1. Clone the repository:

```
git clone https://github.com/khsadeen/Flexi-ATM-project.git
```

2. Open the project using a Java development environment such as IntelliJ IDEA, Eclipse, or NetBeans.

3. Ensure that the Java Development Kit (JDK) is properly configured.

4. Compile and run the main application file:

```
App.java
```

5. The system interface will start, allowing the user to interact with the ATM simulation.

---

## Educational Objectives

This project was developed in order to demonstrate and practice several important software engineering concepts:

* Implementation of Object-Oriented Programming principles
* Design of modular software architecture
* Development of graphical user interfaces using Java Swing
* Implementation of financial transaction logic
* Integration of notification services

---

## Future Work

Possible extensions and improvements for the system include:

* Integration with a persistent database system
* Implementation of secure authentication mechanisms
* Addition of transaction history tracking
* Support for multiple user accounts
* Enhancement of the graphical user interface

---

## Author

Developed by
**Sadeen Khateeb**

---

## License

This project was developed for educational and academic purposes.

