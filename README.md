# Bank System Project

A simulation of a real-world banking system implemented in C++ using a 3-tier architecture.

## Overview

The Bank System project is designed to reflect the intricacies of real-world banking operations in a scalable and maintainable manner. Leveraging the principles of object-oriented programming (OOP) and clean code practices, this project embodies efficiency and clarity in its structure.

## Key Features

### 3-Tier Architecture

Separation of UI, Business, and Database layers for enhanced modularity and maintainability.

### File Handling with C++ "fstream"

Utilizes the power of C++ and the fstream library for seamless data storage and retrieval.

### Object-Oriented Programming

The project embraces key OOP concepts to ensure robustness and flexibility:

- Classes and Objects: Extensive use of classes and objects for encapsulation and abstraction.
- Encapsulation: Protects the internal state of objects, restricting access to only necessary components for improved security and maintainability.
- Inheritance and Polymorphism: Enhances code reusability and readability through inheritance and polymorphic behaviors.
- Abstraction: Focuses on essential properties and behaviors, hiding unnecessary details to simplify complexity.

### Clean Code 

The implementation adheres to some clean code principles:

- Fixed Naming Conventions: Consistent naming methods across the system for improved clarity.
- Readability: Ensures the codebase is easy to understand and navigate.
- Maintainability: Designed for ease of maintenance, reducing the cost of future updates.

### Screens and Functionality

The system comprises over 20 screens, each embodying clean code practices. The flow of screens facilitates an intuitive user experience, mirroring real-world banking interactions.

## Main Features

1. **Login Screen**

   - The system user can only access the system with an existing username and password.
   - Users have three attempts to log in successfully; otherwise, the system will close automatically.

   [Screenshot: Login Screen]

2. **Main Screen**

   - After a successful login, the main screen with 10 options is displayed to the user.

   [Screenshot: Main Screen]

3. **Access to System Features**

   - Only admins can access all system features.
   - Other users are granted access to specific features. Unauthorized attempts result in denial.

   [Screenshot: Unauthorized Access]

4. **Manage Clients**

   - Users can add, delete, update, and find clients.

   [Screenshot: Manage Clients]

5. **Make Transactions**

   - Perform various transactions: deposit, withdraw, transfer between accounts, and view transfer logs.

   [Screenshot: Transactions]

6. **Manage Users**

   - Admins can add, delete, update, find, and view the list of users.

   [Screenshot: Manage Users]

7. **Show Login Registers**

   - View login records for basic security.

   [Screenshot: Login Registers]

8. **Currency Exchange Integration**

   - Merged currency exchange project for seamless currency operations.

   [Screenshot: Currency Exchange Integration]

Feel free to incorporate actual screenshots in the respective sections to provide visual context for each feature.
