# Improved_Patient_Admission_Management_System
A console-based Hospital Management System developed using Java, implementing core Object-Oriented Programming (OOP) concepts. The system allows users to manage patient records efficiently with full CRUD operations and data persistence using file handling with Improved Code quality and Error Handling.

## Features
Add new patients with ID, name, age, gender, disease, and contact number

View all patient records in a structured format

Update patient details by ID

Delete patient records safely

Validate inputs (ID, name, age, etc.) to prevent incorrect data

Store data persistently using a .txt file in CSV format

Clean, modular codebase using OOP principles and layered architecture

## Project Structure
bash
Copy
Edit
HospitalManagementSystem/
├── model/           # Patient data model
│   └── Patient.java
├── dao/             # File data access operations
│   └── PatientDAO.java
├── service/         # Business logic layer
│   └── PatientService.java
├── util/            # File utility functions
│   └── FileUtil.java
├── Main.java        # Console UI and event handling
├── patients.txt     # Data storage file
🔧 Technologies Used
Java 17+

Console I/O

Java Collections

File Handling (java.io, java.nio.file)

OOP Design (Encapsulation, Abstraction, Layered Architecture)


## Future Enhancements
GUI using JavaFX or Swing

Switch from text file to database (MySQL/PostgreSQL)

Role-based login (Admin, Receptionist)

PDF/Excel export of patient records

REST API or Web UI using Spring Boot

