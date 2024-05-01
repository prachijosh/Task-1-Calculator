Introduction:
The provided Java program is a simple calculator that allows users to perform basic arithmetic operations, such as addition, subtraction, multiplication, and division. It interacts with the user through a console interface, providing a menu for operation selection and prompting the user to enter two numbers for the chosen operation. The program then displays the result of the operation or an error message in the case of division by zero.

Explanation:
The program utilizes the Scanner class to take user input and employs a modular approach with functions for each arithmetic operation (addition, subtraction, multiplication, and division). The main method acts as the entry point, guiding the user through the process of selecting an operation and entering numerical values. The switch statement is employed to execute the appropriate operation based on the user’s choice, and the program ensures that division by zero is handled to prevent runtime errors.

Algorithm:
Display Menu:
Print a menu displaying available arithmetic operations: add, subtract, multiply, and divide.
Prompt the user to enter a choice (1-4).
Input Numbers:
Prompt the user to enter two numbers for the chosen operation.
Perform Operation:
Use a switch statement to determine the selected operation.
Call the corresponding function (add, subtract, multiply, or divide) with the provided numbers.
Display the result or an error message for division by zero.
Close Scanner:
Close the Scanner object to release resources.
Arithmetic Functions:
Separate functions for addition, subtraction, multiplication, and division perform the respective mathematical operations.
