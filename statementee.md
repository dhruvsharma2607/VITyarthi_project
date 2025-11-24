statement.md
1. Problem Statement

Managing student information manually often leads to several challenges. Teachers, administrators, and students may struggle with misplaced records, time-consuming searches, inconsistent updates, and disorganized data. Without a structured digital system, even simple tasks such as verifying a student’s course, CGPA, or state of residence become inefficient and prone to errors.

This project addresses these issues by implementing a simple yet effective Student Record Management System using Python. By storing student information in nested dictionaries, the system ensures fast access, easy updates, and clean organization of data—all within a single file.

2. Scope of the Project

The scope of this project is intentionally focused and beginner-friendly. It includes the essential components needed for managing student records in a small-scale environment such as a classroom, school practice lab, or learning exercise.

Within the current scope, the system provides:

A menu-driven interface for user interaction

Management of student details such as registration number, name, course, CGPA, and state

CRUD functionality: Create, Read, Update, Delete

Storage of all records directly in memory using nested dictionaries

Output displayed neatly in the terminal

However, the system does not include advanced features such as persistent file storage, databases, or graphical interfaces. The goal is to maintain simplicity while demonstrating fundamental programming concepts.

3. Target Users

This project is designed for:

1. Students learning Python

Those who want hands-on experience with dictionaries, functions, decision-making, loops, and input handling.

2. Educators and instructors

Teachers who need a simple demonstration tool for explaining data structures, CRUD operations, or menu-driven programs.

3. Beginners building their first Python projects

Anyone looking to understand how small command-line applications are designed and structured.

4. Hobby programmers

Users who want to expand or modify the system by adding file storage, GUIs, or additional features.

4. High-Level Features

The system provides the following major features:

1. Add Student Records

Users can input a student’s details—including registration number, name, course, CGPA, and state—which are stored in a nested dictionary.

2. Search for a Student

A registration number can be used to quickly locate and display a specific student’s details.

3. Update Existing Details

Any part of a student’s record (name, course, CGPA, or state) can be updated based on user selection.

4. Delete Student Records

Complete removal of a student’s data by specifying their registration number.

5. Display All Records

Prints all student information in a structured, readable format.

6. Single-File, No Dependencies

Everything runs in a single Python file (student.py) without the need for external libraries, files, or databases.
