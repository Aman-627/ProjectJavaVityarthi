Campus Course & Records Manager (CCRM)
📌 Overview
The Campus Course & Records Manager (CCRM) is a console-based Java SE application designed to simplify academic administration within an educational institution. It allows students, instructors, and admins to manage courses, enrollments, and grades through a user-friendly Command Line Interface (CLI).

The project demonstrates key Object-Oriented Programming (OOP) concepts like Encapsulation, Inheritance, and Polymorphism, alongside modern Java features.

✨ Features
Student & Instructor Management: Handle creation, updates, and transcript generation for students.

Course Management: Allows for the creation, modification, searching, and filtering of courses.

Enrollment & Grading System: Enroll students, record marks, compute GPA, assign grades, and generate academic reports.

File Operations: Import and export data using CSV format.

Backup & Restore: Includes functionality for data backup and restoration using Java NIO.2 and recursive directory utilities.

Menu-based CLI Interface: Provides user-friendly text-based navigation for all functions.

🛠 Project Structure
The project is organized into the following packages:

edu/
└── ccrm/
    ├── cli/          # Handles the command-line interface and user interaction (MainApp.java)
    ├── config/       # Contains application configuration
    ├── domain/       # Core entity classes (Student.java, Course.java, etc.)
    ├── io/           # Services for data import/export
    ├── service/      # Business logic for managing entities
    └── util/         # Utility classes, including recursion examples
⚙️ Requirements
Java JDK 17 or above.

A terminal or command prompt.

(Optional) An IDE like Eclipse or IntelliJ IDEA.

▶️ How to Run
Method 1: Simple Execution (Using Command Script)
Download and place the project folder on your desktop.

Open the cmd file with a text editor like Notepad.

In the line cd /d C:\Users\Atman\Desktop, change \Atman\ to your own user profile name to match your desktop path, then save the file.

Run the .cmd file to start the application.

Method 2: Using an IDE (Eclipse Example)
Clone the repository.

Launch Eclipse and select a workspace.

Create a new Java Project: Go to File → New → Java Project. Enter a project name and ensure the JDK version is set to Java 17 or newer.

Add Source Files: Create a source folder named src. Inside src, create the necessary packages (e.g., edu.ccrm.cli, edu.ccrm.domain) and add the .java files into their respective packages.

Set Run Configuration:

Right-click on the main class (MainApp.java) and select Run As → Java Application.

Alternatively, go to Run → Run Configurations..., create a new Java Application configuration, and set the Main class to edu.ccrm.cli.MainApp.

Run the application. The main menu will appear in the console.

Installing & Configuring Java on Windows
Step 1: Download the JDK
Open a browser and navigate to Oracle JDK Downloads or Adoptium.

Select a Java SE Development Kit (JDK), such as JDK 17 LTS.

Download the Windows x64 Installer (.exe).

Step 2: Install the JDK
Run the downloaded installer.

Follow the setup wizard, accepting the license agreement and choosing an installation path (e.g., C:\Program Files\Java\jdk-17).

Step 3: Set Environment Variables
Open System Properties by searching for "Environment Variables" in the Windows Search bar.

Under System variables, click New... and add a JAVA_HOME variable:

Variable name: JAVA_HOME

Variable value: C:\Program Files\Java\jdk-17 (your installation path)

Find the Path variable, select it, and click Edit.... Click New and add %JAVA_HOME%\bin.

Click OK to save all changes.

Step 4: Verify Installation
Open a new Command Prompt (cmd).

Run java --version to check the Java runtime version.

Run javac --version to check the Java compiler version.

(Screenshots of these steps were included in the original documentation).

Technical Concepts Demonstrated
This project demonstrates several core Java and OOP principles:

Syllabus Topic	File / Class / Method Where Demonstrated
Encapsulation	Student.java
Inheritance	Person.java → Student.java, Instructor.java
Polymorphism	TranscriptService interface and its implementation
Streams & Lambdas	CourseServiceImpl.filterCoursesByDept()
Enums	Semester.java, Grade.java
Exception Handling	DuplicateEnrollmentException
NIO.2	ImportExportService, BackupService
Recursion	RecursionUtil.computeBackupSize()
Date/Time API	Enrollment.java

Export to Sheets
Enabling Assertions
To run the application with assertions enabled for debugging and validation, use the -ea flag:

Bash

java -ea -cp bin edu.ccrm.cli.MainApp
Appendix: Java Platform Explained
Evolution of Java
1995: Java 1.0 - Introduced the "Write Once, Run Anywhere" philosophy.

2004: Java 5 - A major update that brought Generics, Enums, and Annotations.

2014: Java 8 - A landmark release introducing Lambda expressions, the Streams API, and a new Date/Time API.

2017: Java 9 - Introduced the Java Platform Module System (JPMS).

2021: Java 17 (LTS) - The current Long-Term Support version, which added Records and Sealed Classes.

Java Editions: SE, EE, and ME
Java SE (Standard Edition): The core Java platform. It provides all the essential libraries and APIs for building general-purpose desktop and console applications. This project is built using Java SE.

Java EE (Enterprise Edition): Now known as Jakarta EE, this edition extends Java SE with APIs for building large-scale, distributed enterprise applications, such as web services and complex business systems.

Java ME (Micro Edition): A lightweight subset of Java designed for resource-constrained environments like mobile phones, sensors, and IoT devices.

JDK vs JRE vs JVM
JVM (Java Virtual Machine): An abstract machine that executes compiled Java bytecode. It is the component that allows Java to be platform-independent.

JRE (Java Runtime Environment): The software package that provides the JVM along with the standard Java class libraries needed to run Java applications.

JDK (Java Development Kit): The complete software development kit for Java. It includes the JRE as well as development tools like the compiler (javac), debugger, and archiver (jar) needed to create Java applications.
