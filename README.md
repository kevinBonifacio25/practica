# practica
practica riwi

#Student Registration System (CRUD)
This is a Python program designed to efficiently manage student registration. The system performs basic CRUD operations (Create, Read, Update, and Delete) by interacting with JSON files for data persistence.
# Features
The program includes the following main functionalities:

    Dynamic Registration: Register multiple students by capturing their ID, name, age, course, and status.
    General Inquiry: Displays a detailed list of all currently registered students.
    Specific Search: Quickly locates a student using their unique identification number (ID).
    Data Update: Allows modifying the status, course, and age of an existing student.
    Record Deletion: Permanently removes students from the system.
    Data Persistence: Changes are automatically saved to a local file through a file management module (crud.py).

# Code Structure
The project is organized into modular functions to facilitate maintenance:

    register_students(): Manages the input of new data.
    show_student_list(): Formats and displays student information on the screen.
    search_students(): Implements the filtering logic by ID.
    update_student(): Enables editing of critical student fields.
    delete_student(): Handles the logic for removing elements from the list.

# Requirements

    Python 3.x
    recyclable_functions module: Used for numeric input validation.
    crud module: Used for saving and loading data in JSON format.

# Usage Example
Upon running the program, you can interact with the registration panel:
text

---REGISTRATION PANEL---
Enter the number of students: 1
Registering student 1 of 1:
Enter the student ID: 101
Enter the student name: Juan Perez
...
