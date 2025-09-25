# Educational Course & Enrollment Management System

## Overview
This is a Java-based **Educational Course & Enrollment Management System**.  
It allows students, instructors, and admins to manage courses, enrollments, and grades through a **Command Line Interface (CLI)**.  

The project demonstrates **Object-Oriented Programming (OOP)** concepts like Encapsulation, Inheritance, and Builder Pattern.

---

## Features
- **Course Management** – Create and manage courses  
- **Enrollment Management** – Enroll students into courses  
- **Instructor Management** – Assign instructors to courses  
- **Grading System** – Assign and view student grades  
- **Menu-based CLI Interface** – User-friendly text-based navigation  

---

## Description 
This project implements a Course and Student Management System in Java, designed to handle course enrollment, student records, and CSV-based data import/export efficiently. The approach emphasizes object-oriented principles and modern design patterns: the Course class is implemented using the Builder pattern to ensure immutability and flexible construction, while the Instructor and Student classes encapsulate personal and institutional data with proper getters and meaningful toString() representations. The system provides a console-based menu interface (Menu.java) for adding, listing, importing, and exporting students and courses. CSV utilities are implemented in CsvUtils.java to facilitate easy data interchange, with proper handling of instructor names, semesters, and departments. When importing courses from CSV files, the system dynamically creates Instructor objects with placeholder details for email and employee ID, ensuring data consistency while allowing for future updates. Overall, the project combines clean code architecture, robust input handling, and CSV integration to create a maintainable and extensible academic management tool.

---
## 🛠 Project Structure
edu/

└── ccrm/

├── Main.java # Entry point of the application

├── cli/

│ └── Menu.java # Command-line interface (menu system)

├── config/

│ └── AppConfig.java # Application configuration

├── domain/

│ ├── Course.java # Course entity

│ ├── Enrollment.java # Enrollment entity

│ ├── Grade.java # Grade entity

│ ├── Instructor.java # Instructor entity

│ ├── Person.java # Base class for people (students/instructors)

│ └── Name.java # Name handling class

└── README.md # (This file)

## ⚙️ Requirements
- Java JDK 11 or above  
- A terminal/command prompt  
- (Optional) An IDE like IntelliJ IDEA, Eclipse, or VS Code  

---

## ▶️ How to Run / Useage
Step 1 - just download and paste this folder on your desktop .

Step 2 - go the cmd file open it with notepad ,  change "C:\Users\Atman\Desktop" in cd /d C:\Users\Atman\Desktop to with your desktop path, save the file .

Step 3 - run the cmd . 

