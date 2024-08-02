# 🍽️ Mess Management System

## Overview
The Mess Management System is a comprehensive solution designed to streamline operations and enhance efficiency in managing mess facilities within educational institutions or similar settings. This system encompasses various modules such as user management, meal booking, feedback handling, inventory management, and administrative functionalities to cater to the diverse needs of mess operations.

## Features
- 👥 **User Management**: Admins, managers, and students are provided with distinct roles and access levels to ensure secure and controlled system usage.
- 🍽️ **Meal Booking**: Students can conveniently book their meals for different times of the day (breakfast, lunch, dinner) through the system.
- 📝 **Feedback Handling**: Students can submit feedback regarding the quality of meals or other aspects of mess operations, which admins can review and respond to.
- 📦 **Inventory Management**: Managers can track and manage the inventory of ingredients to ensure smooth meal preparation and avoid shortages.
- 🗓️ **Leave Application**: Students can apply for leave from mess services for specific periods, with managers having the authority to approve or reject such requests.

## Technologies Used
- 🗄️ **MySQL**: The relational database management system is utilized to store and manage data related to users, meals, feedback, inventory, and other aspects of the system.
- ☕ **Java**: Core programming language used for backend logic and business rule implementation.
- 🎨 **JavaFX**: Framework utilized for building the graphical user interface (GUI) to provide an interactive user experience.
- 🔗 **JDBC**: Java Database Connectivity API used for establishing connections between the Java application and the MySQL database.

## Database Schema
The MySQL database schema for the Mess Management System includes the following tables:
- `admin`: Stores information about system administrators.
- `mess`: Contains details of different mess facilities.
- `student`: Stores data regarding students, including their hostel, room number, and associated mess.
- `feedback`: Stores feedback submitted by students.
- `leave_apply`: Manages leave applications submitted by students.
- `leftover`: Tracks leftover food items in the mess.
- `manager`: Stores details of mess managers.
- `meal_owner`: Manages meal ownership and associated student IDs.
- `meal_booking`: Tracks meal bookings made by students.
- `requests`: Manages meal requests made by students, including food packages and addons.
- `responds`: Stores responses provided by admins to student feedback.

## Installation

### MySQL Database Setup:
1. 🛠️ Execute the provided SQL script in MySQL Workbench or any MySQL client to create the necessary database schema and tables.

### Java Development Environment Setup:
1. ☕ Ensure you have Java Development Kit (JDK) installed on your system.

### Project Configuration:
1. 🔧 Update the database connection settings in the Java application code to connect to your MySQL database.

### Compile and Run:
1. 🖥️ Compile the Java source files using any Java IDE or command-line tools.
2. 🚀 Run the application to start the Mess Management System.

## Usage

### Login:
1. 🔑 Use your credentials to log in to the system based on your role (admin, manager, or student).

### Navigate Through Modules:
1. 📂 Explore various modules such as meal booking, feedback submission, leave application, and inventory management based on your role and permissions.

### Perform Actions:
1. ✅ Perform actions such as booking meals, submitting feedback, managing inventory, or responding to leave applications based on your role within the system.

## Contributors
- **Aman Rameshchandra Agrawal**
- **Sanchit Kabra**
- **Kshitiz Gupta**
## Google Drive Link
- 📚 [Mess Management System Project Folder](https://drive.google.com/drive/folders/1yFEVyEvQB_KlAqes5mDR8Z1uqBuoQY-J?usp=drive_link)
## Acknowledgements
- 📚 [MySQL Documentation](https://dev.mysql.com/doc/)
- 📚 [JavaFX Documentation](https://openjfx.io/)
- 📚 [JDBC Documentation](https://docs.oracle.com/javase/8/docs/technotes/guides/jdbc/)
- 💡 [Stack Overflow](https://stackoverflow.com/) - for troubleshooting and guidance
