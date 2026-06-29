# codealpha_tasks
1. SIMPLE CALCULATOR IN C

 Description

This is a simple command-line calculator program written in C. It allows users to perform basic arithmetic operations using the switch statement.

 Features
 Addition

 Subtraction

 Multiplication

 Division

 Handles division by zero

 User-friendly menu-driven interface

 Technologies Used

C Programming Language

Standard C Library (stdio.h)

 How to Compile and Run

Using GCC

Compile the program:

gcc calculator.c -o calculator

Run the program:

./calculator

Example Output

Enter first number: 15
Enter second number: 5

Select Operation:
1. Addition
2. Subtraction
3. Multiplication
4. Division
Enter choice (1-4): 4

Result = 3.00

 How It Works

Enter the first number.

Enter the second number.

Choose an operation from the menu.

The program calculates and displays the result.

If division by zero is attempted, an error message is displayed.

 Future Improvements

Perform multiple calculations without restarting the program.

Add modulus (%) operation.

Add power and square root operations.
------------
2.STUDENT MANAGEMENT SYSTEM

Student Management System in C

 Description

The Student Management System is a console-based application developed in C that uses file handling to store and manage student records. It allows users to perform basic CRUD (Create, Read, Update, Delete) operations on student data.

 Features

-  Add new student records
-  Display all student records
-  Search for a student by roll number
-  Update existing student details
-  Delete student records
-  Store records permanently using binary file handling
-  Menu-driven interface

 Technologies Used

- C Programming Language
- Standard C Libraries:
  - "stdio.h"
  - "stdlib.h"
  - "string.h"

 How to Compile and Run

Using GCC

Compile the program:

gcc student_management_system.c -o student_management_system

Run the program:

Linux/macOS

./student_management_system

Windows

student_management_system.exe

 Menu Options

===== Student Management System =====
1. Add Student
2. Display Students
3. Search Student
4. Update Student
5. Delete Student
6. Exit

 How It Works

1. Start the program.
2. Choose an option from the menu.
3. Enter student details when prompted.
4. Student records are saved in the "students.dat" file.
5. You can search, update, display, or delete records at any time.
6. Exit the program when finished.

 Example Output

===== Student Management System =====
1. Add Student
2. Display Students
3. Search Student
4. Update Student
5. Delete Student
6. Exit

Enter your choice: 1

Enter Roll Number: 101
Enter Name: John Doe
Enter Marks: 89.5

Student Record Added Successfully!

 File Handling

This project uses binary file handling to store student information in the "students.dat" file, ensuring data is retained even after the program is closed.

 Future Improvements

- Prevent duplicate roll numbers.
- Add student grade calculation.
- Sort records by roll number, name, or marks.
- Add attendance management.
- Export records to a text or CSV file.
- Improve input validation and error handling.
- Create a graphical user interface (GUI).
  --------------

3.MATRIX CALCULATION IN C

Matrix Operations in C

 Description

This project is a simple Matrix Operations program written in C. It performs common matrix operations such as matrix addition, matrix multiplication, and matrix transpose using user-provided input.

 Features

-  Matrix Addition
-  Matrix Multiplication
-  Matrix Transpose
-  Accepts matrix input from the user
-  Displays results in a clear format

 Technologies Used

- C Programming Language
- Standard C Library ("stdio.h")

 How to Compile and Run

Using GCC

Compile the program:

gcc matrix_operations.c -o matrix_operations

Run the program:

Linux/macOS

./matrix_operations

Windows

matrix_operations.exe

 Example Input

Enter rows and columns of matrices:
2 2

Enter elements of Matrix A:
1 2
3 4

Enter elements of Matrix B:
5 6
7 8

 Example Output

Matrix Addition:
6 8
10 12

Matrix Multiplication:
19 22
43 50

Transpose Matrix:
1 3
2 4

 How It Works

1. Enter the number of rows and columns.
2. Input the elements of Matrix A.
3. Input the elements of Matrix B.
4. The program performs:
   - Matrix Addition
   - Matrix Multiplication
   - Transpose of Matrix A
5. The results are displayed on the screen.

 Note

- Matrix addition requires both matrices to have the same dimensions.
- Matrix multiplication is valid only when the number of columns in the first matrix equals the number of rows in the second matrix. This implementation assumes compatible dimensions.
- The transpose operation is performed only on Matrix A.

 Future Improvements

- Add matrix subtraction.
- Support matrices with different dimensions for multiplication.
- Implement determinant and inverse operations.
- Improve input validation and error handling.
- Add a menu-driven interface for selecting operations.

 Author

JHARNA RANI BHAKAT
