# Student Record Management System using Python (Menu-Driven, Nested Dictionary)

# 1.Problem Definition

Managing student information manually leads to:

Errors in data entry

Difficulty in searching records

Missing or duplicate details

Lack of data organization

To solve this, a simple command-line Student Record System is developed using Python. It stores multiple students using a nested dictionary, allowing efficient storage and retrieval.



 # 2. Objectives

The system aims to:

1 Add new student records

2 Search for a student by Registration Number

3 Update existing student details

4 Delete a student record

5 Display all stored records

6 Use a menu-driven approach

Keep data structured in a nested dictionary


# 3. Software & Hardware Requirements
 #Software

Python 3.8+

VS Code / IDLE / PyCharm (any editor)

Windows/Linux/Mac OS

#Hardware

Any standard PC or laptop

Minimum 4 GB RAM



# 4. System Design

The system uses:

Nested Dictionary

students = {"101": 
              {"name": "John",
               "course": "BCA",
               "cgpa": 8.5,
               "state": "Kerala"}}




# 5. Modular Structure

The program is divided into the following functions:

1.add_student()

2.search_student()

3.update_student()

4.delete_student()

5.display_all()

6.main_menu()




# 6. Algorithm

Main Program Algorithm
1. Start
2. Initialize an empty dictionary “students”
3. Repeat until user chooses Exit:
       a. Display menu
       b. Read user choice
       c. If choice is:
             1 → add_student()
             2 → search_student()
             3 → update_student()
             4 → delete_student()
             5 → display_all()
             6 → Exit
4. End



# 7. Function Algorithms:

7.1 add_student()

1. Input registration number
2. If reg number already exists → show message
3. Else:
   a. Input name, course, CGPA, state
   b. Store inside nested dictionary
4. Display success message

7.2 search_student()

1. Input registration number
2. If exists:
       Display full details
   Else:
       Show “not found”

7.3 update_student()

1. Input registration number
2. If exists:
      Ask user which field to update
      Update value
   Else:
      Show “not found”

7.4 delete_student()

1. Input registration number
2. If exists:
       Delete that key from dictionary
   Else:
       Show “not found”

7.5 display_all()

1. If dictionary empty → show message
2. Otherwise:
      Loop through all keys and print details

# 8. Sample Menu UI

===== STUDENT RECORD SYSTEM =====
1. Add Student
2. Search Student
3. Update Student
4. Delete Student
5. Display All Students
6. Exit
Enter your choice:


# 9. Sample Input / Output

Add Student
Enter Register Number: 101
Enter Name: Ravi
Enter Course: CSE
Enter CGPA: 8.2
Enter State: M.P
Student added successfully!



# 10. Advantages

Simple, fast, and user-friendly

No external files needed

Easy to modify and extend

Efficient data structure (nested dictionary)



# 11. Limitations

Data is lost when program closes

No file storage

Only CLI interface

No validations for CGPA/State (optional upgrade)

# 12. Target Users

1. Beginner Python Learners
2. School & College Students
3. Instructors & Educators
4. Beginners Practicing Data Handling

# 13. Future Enhancements

We can add:

1.File handling (JSON / CSV)

2.GUI using Tkinter

3.Database (MySQL / SQLite)

4.Auto-generated registration numbers
