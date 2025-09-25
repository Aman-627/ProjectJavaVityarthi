# Educational Course & Enrollment Management System

##  Overview
This is a Java-based **Educational Course & Enrollment Management System**.  
It allows students, instructors, and admins to manage courses, enrollments, and grades through a **Command Line Interface (CLI)**.  

The project demonstrates **Object-Oriented Programming (OOP)** concepts like Encapsulation, Inheritance, and Builder Pattern.

---
Evolution of Java
1995: Java 1.0 - Introduced the "Write Once, Run Anywhere" philosophy.

2004: Java 5 - A major update that brought Generics, Enums, and Annotations.

2014: Java 8 - A landmark release introducing Lambda expressions, the Streams API, and a new Date/Time API.

2017: Java 9 - Introduced the Java Platform Module System (JPMS).

2021: Java 17 (LTS) - The current Long-Term Support version, which added Records and Sealed Classes.

---

##  Features
- **Course Management** – Create and manage courses  
- **Enrollment Management** – Enroll students into courses  
- **Instructor Management** – Assign instructors to courses  
- **Grading System** – Assign and view student grades  
- **Menu-based CLI Interface** – User-friendly text-based navigation  

---
Java Editions: SE, EE, and ME
Java SE (Standard Edition): The core Java platform. It provides all the essential libraries and APIs for building general-purpose desktop and console applications. This project is built using Java SE.

Java EE (Enterprise Edition): Now known as Jakarta EE, this edition extends Java SE with APIs for building large-scale, distributed enterprise applications, such as web services and complex business systems.

Java ME (Micro Edition): A lightweight subset of Java designed for resource-constrained environments like mobile phones, sensors, and IoT devices.

JDK vs JRE vs JVM
JVM (Java Virtual Machine): An abstract machine that executes compiled Java bytecode. It is the component that allows Java to be platform-independent.

JRE (Java Runtime Environment): The software package that provides the JVM along with the standard Java class libraries needed to run Java applications.

JDK (Java Development Kit): The complete software development kit for Java. It includes the JRE as well as development tools like the compiler (javac), debugger, and archiver (jar) needed to create Java applications.

---

## Project Structure
The project directory is organized by feature, with distinct packages for the user interface, domain objects, and services. The visual layout below highlights the key files and their roles:
```

edu/
└── ccrm/
    ├── cli/
    │   └── MainApp.java        # Entry point of the application & main menu system
    ├── domain/
    │   ├── Person.java         # Base class for Student and Instructor
    │   ├── Student.java        # Student entity demonstrating Encapsulation
    │   ├── Course.java         # Course entity
    │   ├── Enrollment.java     # Enrollment entity using the Date/Time API
    │   └── Grade.java          # Grade enum
    ├── service/
    │   └── CourseServiceImpl.java # Business logic, uses Streams & Lambdas
    ├── io/
    │   └── ImportExportService.java # Handles CSV data operations using NIO.2
    └── README.md                 # (This file)

```
    
## Requirements
Java JDK 17 or above


##  How to Run
Step 1 - just download and paste this folder on your desktop .
Step 2 - go the cmd file open it with notepad ,  change '\Atman\' in cd /d C:\Users\Atman\Desktop to your desktop path, save the file .
Step 3 - run the cmd . 
