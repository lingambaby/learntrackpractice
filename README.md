# LearnTrack – Student & Course Management System

## Project Summary
LearnTrack is a console-based Student & Course Management System built using Core Java.
It allows administrators to manage students, courses, and enrollments through a
menu-driven console application.

This project is designed to strengthen Core Java fundamentals including OOP,
collections, exception handling, and clean code practices.

## Features
### Student Management
- Add new students
- View all students
- Search student by ID
- Deactivate a student (soft delete)

### Course Management
- Add new courses
- View all courses
- Activate / Deactivate courses

### Enrollment Management
- Enroll students into courses
- View enrollments for a student
- Mark enrollment as COMPLETED or CANCELLED

## Technologies Used
- Java (Core Java)
- JDK 17 (or your version)
- ArrayList
- Console-based UI


## Package Structure
- entity – Core domain classes (Student, Course, Enrollment)
- service – Business logic
- ui – Console-based menu and user interaction
- exception – Custom exceptions
- util – Utility/helper classes
## Class Diagram
Person
 └── Student

Student → Enrollment ← Course

## How to Compile and Run
1. Open the project folder on your system
2. Navigate to the src folder
3. Compile the project:
   javac com/airtribe/learntrack/Main.java
4. Run the application:
5. java com.airtribe.learntrack.Main
