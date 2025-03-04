### CollegeManagementSystem [Console Based Project]

# Overview
The CollegeManagementSystem is a console-based Python application that allows users to manage colleges, students, and teachers. The system provides functionality to create colleges, add students and teachers, and display their details.

# Features
-  Create a college with a unique ID and name.
-  Add teachers to a college with details like name, email, and subject.
-  Add students to a college with details like name, email, and branch.
-  Display details of all teachers in a college.
-  Display details of all students in a college.
-  Console-based user-friendly menu for interaction.

# Technologies Used
-  Python

# Installation
-  Clone the repository:
  git clone https://github.com/yourusername/CollegeManagementSystem.git
-  Navigate to the project directory:
  cd CollegeManagementSystem
-  Run the script:
  python college_management.py

# Usage
Run the script and choose from the available options:
-  Create a college.
-  Add a teacher.
-  Add a student.
-  Display teacher details.
-  Display student details.
-  Exit the application.

# Code Structure
-  Person Class: Base class with name and email attributes.
-  Student Class: Inherits from Person, with an additional branch attribute.
-  Teacher Class: Inherits from Person, with an additional subject attribute.
-  College Class: Manages students and teachers, provides methods to add/display them.
-  Main Execution: A loop-based menu for user interaction.

# Example Output
Choose your Option:
1. To Create College
2. To Add Teacher
3. To Add Student
4. To Display Teacher Details
5. To Display Student Details
6. Exit
Enter Your Option: 1
Enter College Id: 101
Enter College Name: ABC College

College Created Successfully

# Contributing
If you wish to contribute:
-  Fork the repository.
-  Create a new branch.
-  Make your changes and commit them.
-  Push to your fork and submit a pull request.

# License
This project is licensed under the MIT License.


