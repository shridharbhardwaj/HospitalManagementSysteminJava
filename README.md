# HospitalManagementSystem

# Overview
The Hospital Management System is a Java-based application designed to manage patient records, doctor schedules, and appointments within a hospital setting. It utilizes Oracle as a local database for data storage and retrieval. Key functionalities include adding patients, viewing patient information, managing doctor schedules, and booking appointments.

# Features
Patient Management: Add new patients and view existing patient records.
Doctor Management: View doctor schedules and availability.
Appointment Booking: Schedule appointments between patients and doctors.
Database Integration: Uses Oracle as a local database for storing patient and doctor information.
Prepared Statements: Implements prepared statements for secure database interactions.
Java Libraries: Utilizes various Java libraries for GUI development, database connectivity, and date/time handling.

# Technologies Used
Java: Core programming language used for application development.
Oracle Database: Local database management system used for data storage.
Swing: Java's GUI toolkit for developing the user interface.
JDBC: Java Database Connectivity API for interacting with the Oracle database.
Java.util.Date: Java standard library for handling date and time operations.
Maven: Dependency management tool for managing project dependencies.

# Setup Instructions
Prerequisites
Java Development Kit (JDK) installed (version X.X or higher)
Oracle Database installed and configured
Maven installed (optional for building and managing dependencies)

# Steps to Run the Application
1. Clone the Repository:
git clone https://github.com/shridharbhardwaj/HospitalManagementSystem.git
cd hospital-management-system

2. Setup Oracle Database:
Create a new schema and tables as per the database schema script provided (database_schema.sql).
Update database connection details (jdbc.url, jdbc.username, jdbc.password) in config.properties file.

3. Compile and Build:

If using Maven:
mvn clean install

4. Run the Application:
java -jar hospital-management-system.jar
Replace hospital-management-system.jar with the actual name of your executable JAR file.

# Usage
Upon running the application, you will be presented with a login screen where you can authenticate as an admin or a user.
Admins have full access to patient management, doctor management, and appointment booking functionalities.
Users have limited access, such as viewing patient records and booking appointments.
