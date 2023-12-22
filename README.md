# Bank System Project

A simple and small scale simulation of a real-world banking system implemented in C++ using object oriented programming concepts and 3-tier architecture.

## Overview

The Bank System project is designed to reflect a real-world banking operations in a small scale and simple functionallity. Leveraging the principles of object-oriented programming (OOP) and clean code practices, this project embodies some clarity in its structure.

## Key Features

### 3-Tier Architecture

Separation of UI, Business, and Database layers for enhanced modularity and maintainability.

### File Handling with C++ "fstream"

Utilizes the power of C++ and the fstream library for seamless data storage and retrieval.

### Object-Oriented Programming

The project embraces key OOP concepts to ensure robustness and flexibility:

- Classes and Objects: Use of classes and objects for encapsulation and abstraction.
- Encapsulation: Protects the internal state of objects, restricting access to only necessary components for improved security.
- Inheritance and Polymorphism: Enhances code reusability and readability through inheritance and polymorphic behaviors.
- Abstraction: Focuses on essential properties and behaviors, hiding unnecessary details to simplify complexity.

### Clean Code 

The implementation adheres to some clean code principles:

- Fixed Naming Conventions: Consistent naming methods across the system for improved clarity.
- Readability: Ensures the codebase is easy to understand and navigate.
- Maintainability: Designed for ease of maintenance, reducing the cost of future updates.

### Screens and Functionality

The system contains over 20 screens, mirroring some of real-world bank-system interactions.

## Main Features

1. **Login Screen**

   - The system user can only access the system with an existing username and password.
   - Users have three attempts to log in successfully; otherwise, the system will close automatically.

   ![failed login](https://github.com/MohamedElDegwi/Bank_System/blob/main/Screenshots/Login%20Screen.png)


2. **Main Screen**

   - After a successful login, the main screen with 10 options is displayed to the user.

   ![Main Screen](https://github.com/MohamedElDegwi/Bank_System/blob/main/Screenshots/Main%20Screen.png)


3. **Access to System Features**

   - Only admins can access all system features.
   - Other users are granted access to specific features. Unauthorized attempts result in denial.

   ![Access Denied screen](https://github.com/MohamedElDegwi/Bank_System/blob/main/Screenshots/Access%20Screen.png)


4. **Manage Clients**

   - Users can add, delete, update, and find clients.
     

5. **Make Transactions**

   - Perform various transactions: deposit, withdraw, transfer between accounts, veiw all clients balances, and view transfer logs.

  ![Transactions Screen](https://github.com/MohamedElDegwi/Bank_System/blob/main/Screenshots/Transactions%20Screen.png)


6. **Manage Users**

   - Admins can add, delete, update, find, and view the list of users.

   ![Manage Users Screen](https://github.com/MohamedElDegwi/Bank_System/blob/main/Screenshots/Manage%20Users%20Screen.png)


7. **Show Login Registers**

   - View login records for basic security.


8. **Currency Exchange Integration**

   - Merged currency exchange project for seamless currency operations.

   ![Currency Exchange Screen](https://github.com/MohamedElDegwi/Bank_System/blob/main/Screenshots/Currency%20Exchange%20screen.png)
