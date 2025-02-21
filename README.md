# basic-calculator
This project implements a simple calculator that can perform basic arithmetic operations such as addition, subtraction, multiplication, and division.

# Description
This is a simple calculator program written in C++ that allows users to perform basic arithmetic operations: addition, subtraction, multiplication, and division. The program provides a menu-driven interface to select the desired operation and input the numbers. The program will continue to run until the user chooses to exit.
**Features**
Addition of two numbers

Subtraction of two numbers

Multiplication of two numbers

Division of two numbers (with error handling for division by zero)

Menu-driven interface

**How to Run**
Compile the Program: Use a C++ compiler to compile the calculator.cpp file.
``sh
g++ calculator.cpp -o calculator```
``
Run the Program: Execute the compiled program.
``sh
./calculator
``
**usage**
Run the program.

You will see a menu with the following options:

Add

Subtract

Multiply

Divide

Exit

Enter the number corresponding to the operation you want to perform.

If you choose an operation (1-4), you will be prompted to enter two numbers.

The program will perform the operation and display the result.

The menu will be displayed again for further operations. Enter 5 to exit the program.

**Code Explanation**

The program consists of the following main components:

**Function Declarations:**

double add(double a, double b): Returns the sum of a and b.

double subtract(double a, double b): Returns the difference between a and b.

double multiply(double a, double b): Returns the product of a and b.

double divide(double a, double b): Returns the quotient of a divided by b. If b is zero, it displays an error message and returns zero.

**Main Function:**

Prompts the user to enter a choice from the menu.

Based on the user's choice, it prompts for two numbers and performs the selected operation.

Displays the result of the operation.

Continues to display the menu until the user chooses to exit.
