# Calculator
# Overview
This is a basic C++ console application that functions as a simple calculator. It allows the user to perform basic arithmetic operations (addition, subtraction, multiplication, and division) on two numbers. The program will continue to prompt the user for calculations until they choose to exit.

# How It Works
Arithmetic Operations:

The program supports four basic arithmetic operations:
Addition (+)
Subtraction (-)
Multiplication (*)
Division (/)
Each operation is implemented as a separate function: add(), subtract(), multiply(), and divide().
User Interaction:

The user is prompted to enter two numbers.
The user then selects an arithmetic operation by entering a corresponding symbol (+, -, *, /).
The program performs the selected operation and displays the result.
Error Handling:

The program handles division by zero by displaying an error message and returning a result of 0.
Looping for Multiple Calculations:

After each calculation, the user is asked whether they want to perform another calculation.
The loop continues if the user enters 'y' or 'Y', otherwise, the program ends with a thank you message.
