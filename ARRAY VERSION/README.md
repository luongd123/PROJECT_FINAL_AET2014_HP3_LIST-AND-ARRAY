
# Student Management System

This is a student management system implemented in C++ that provides functionalities to manage student data. The system allows you to add, view, search, and display students based on specific criteria like the highest and lowest average grades.

## Features

1. **Add New Student**: Allows users to input and add new students to the system with details such as student code, full name, date of birth, and average grade.
2. **Display All Students**: Displays the list of all students with their details.
3. **Search by Student Code**: Search for a student by their unique student code.
4. **Display Students with the Highest Average Grade**: Displays the student(s) with the highest average grade.
5. **Display Students with the Lowest Average Grade**: Displays the student(s) with the lowest average grade.
6. **Data Persistence**: Student information is saved and loaded from a file (`danhsachsinhvien.txt`), ensuring data is preserved even after the program is closed.

## How to Use

1. Run the program:
    ```bash
    PLEASE RUN THE ONLY .EXE FILE
    ```

2. The following options will be available:

    - **Add new student to the list**: Enter student details like code, full name, date of birth, and average grade.
    - **Display all students**: View a list of all students in the system.
    - **Search for a student by student code**: Search for a specific student by entering their student code.
    - **Display student with the highest average grade**: View the student(s) with the highest grade.
    - **Display student with the lowest average grade**: View the student(s) with the lowest grade.
    - **Exit**: Exit the application.

3. Student data will be saved in the file `danhsachsinhvien.txt`, ensuring data persistence.

## File Format

The file `danhsachsinhvien.txt` stores the student information in the following format:

- The first line contains the number of students in the list.
- Each student’s information is stored in the following order:
    - Student Code
    - Full Name
    - Date of Birth (dd/mm/yyyy)
    - Average Grade
- Do not change the `danhsachsinhvien.txt` file
## Code Explanation

1. **Standardization of Input**: The system ensures that the name is capitalized properly and that the date format is consistent (dd/mm/yyyy).
2. **Validation**: The program validates the student code, date of birth, and average grade to ensure correctness.
3. **Leap Year Check**: The system accounts for leap years when checking the validity of a student's date of birth.

## License

Just build it my self

## Acknowledgments

- The system is built using C++ Standard Library (STL) and basic file handling.
- Special thanks to the creators of C++ documentation and tutorials.

## For Examiner 

- Thank you, teacher, for reviewing my code. I have added detailed notes for each function, method, and feature in the code. I hope you can provide feedback and help improve my code so that I can perform better in the future.
- 24110215
- Lương Chí Dũng 

*This README.md is written with the support of AI assistance.*  
*THIS PROGRAM CAN NOT RUN WITH A LIST OF 10000 Students or above because i use liner search for searching(to lazy to overload operators, may be i'll do it to apply binary_search or something faster on this program but i think there won't be any school that have more than 10000 studens : DDDDD)*



