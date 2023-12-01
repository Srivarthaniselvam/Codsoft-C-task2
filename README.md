# Codsoft-C-task2

# Simple Calculator Program

This C++ program is a simple calculator that allows users to perform basic arithmetic operations on two numbers. The program uses a do-while loop to enable multiple calculations, and it includes error handling for division by zero and invalid operations.

# Program Structure:

- **User Input:**
  - Users are prompted to enter two numbers and choose an operation (+, -, *, /).
  - Input validation is applied to handle invalid input.

- **Calculation:**
  - The program uses a switch statement to perform the selected operation.
  - Division by zero is checked to prevent runtime errors.

- **Output:**
  - The result of the calculation is displayed.
  - Users are asked if they want to perform another calculation.

- **Loop and Exit:**
  - The program continues running as long as the user wants to perform additional calculations.
  - The loop converts the user's response to lowercase for case-insensitive comparison.

# Error Handling:

- **Division by Zero:**
  - If the user attempts to divide by zero, an error message is displayed, and the program terminates with a return code of 1.

- **Invalid Operation:**
  - If the user enters an invalid operation, an error message is displayed, and the program terminates with a return code of 1.



# How to Use

1. Clone the repository to your local machine.

    ```bash
    git clone https://github.com/your-username/simple-calculator.git
    ```

2. Compile the program using a C++ compiler (e.g., g++).

    ```bash
    g++ simple_calculator.cpp -o simple_calculator
    ```

3. Run the compiled executable.

    ```bash
    ./simple_calculator
    ```

4. Follow the on-screen prompts to enter numbers and choose arithmetic operations.

# Features

- Addition (+)
- Subtraction (-)
- Multiplication (*)
- Division (/)

# Example Usage

Welcome to the Simple Calculator Program!

Enter the first number: 10
Enter the second number: 5
Choose an operation (+, -, *, /): +
Result of (10 + 5): 15

Do you want to perform another calculation? (yes/no): yes

Enter the first number: 8
Enter the second number: 0
Choose an operation (+, -, *, /): /
Error: Division by zero is not allowed.

Thank you for using the calculator. Goodbye!

# sample image 

![sim1](https://github.com/Srivarthaniselvam/Codsoft-C-task2/assets/151417502/80744b74-490d-4add-835b-4c6cb08ac85a)
![sim2](https://github.com/Srivarthaniselvam/Codsoft-C-task2/assets/151417502/a30fb815-5772-4b37-a62b-63a923b8b24b)
![sim3](https://github.com/Srivarthaniselvam/Codsoft-C-task2/assets/151417502/d09828ba-fd76-41fa-b6e9-40bf6d9d9196)
![sim4](https://github.com/Srivarthaniselvam/Codsoft-C-task2/assets/151417502/de2077da-5cc8-41ee-8f47-1bf8ab2189f6)
