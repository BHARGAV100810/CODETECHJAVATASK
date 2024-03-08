# CODETECHJAVATASK
Simple Calculator (TASK -1)
1. Introduction
The Simple Calculator program is a Java application designed to perform basic arithmetic operations. It provides users with a straightforward interface to input two numbers and choose an operation to apply to them.

2. Features
The calculator offers the following features:

Addition: Add two numbers together.
Subtraction: Subtract one number from another.
Multiplication: Multiply two numbers.
Division: Divide one number by another.
3. Usage
3.1 Launching the Program
To start the calculator, execute the program in a Java environment.

3.2 Selecting an Operation
Upon launching the program, the user is prompted to select an operation by entering a corresponding number. The available options are:

Addition
Subtraction
Multiplication
Division
3.3 Entering Numbers
After selecting an operation, the user is prompted to input two numbers. These numbers can be integers or decimals.

3.4 Viewing the Result
Once the numbers are entered, the program calculates the result based on the selected operation and displays it to the user.

4. Error Handling
4.1 Division by Zero
The program checks for division by zero. If the user attempts to divide by zero, an error message is displayed, and the program terminates gracefully.

4.2 Invalid Inputs
Invalid inputs, such as non-numeric characters or incorrect operation selections, prompt the user to enter valid input. The program provides appropriate error messages and guidance.

5. Example
Suppose the user wants to perform an addition operation:

The user launches the program.
Selects addition by entering '1'.
Inputs the first number, for example, '5'.
Inputs the second number, for example, '3'.
The program calculates the result and displays '8'.
6. Dependencies
The Simple Calculator program relies on the Java standard library for basic input/output operations and arithmetic calculations. It does not require any external dependencies.

7. Limitations
7.1 Basic Arithmetic Operations
The calculator supports only basic arithmetic operations, including addition, subtraction, multiplication, and division. It does not handle more advanced mathematical functions.

7.2 Numeric Input Only
The program accepts numeric inputs only. Non-numeric characters are treated as invalid input.

7.3 No Memory Functionality
The calculator does not have memory functionality to store previous results for subsequent calculations.

7.4 Limited Precision
Due to the limitations of floating-point arithmetic, the program may exhibit slight inaccuracies in calculations involving decimal numbers.

This documentation provides a comprehensive overview of the Simple Calculator program, including its features, usage instructions, error handling, example, dependencies, and limitations.



NUMBER GUESSING GAME  (TASK-2)
1. Introduction
The Number Guessing Game is a Java application that allows users to guess a randomly generated number between 1 and 100. The game provides feedback to the user after each guess, informing them whether their guess is too high, too low, or correct. The game ends when the user guesses the correct number or runs out of attempts.

2. Features
Randomly generated number: The game selects a random number between 1 and 100 for the user to guess.
User input validation: The game validates user input to ensure it is a valid integer.
Feedback on guesses: After each guess, the game provides feedback to the user, indicating whether the guess is too high, too low, or correct.
Limited attempts: The user has a maximum of 3 attempts to guess the correct number.
3. Usage
3.1 Starting the Game
Run the program to start the Number Guessing Game.
3.2 Guessing the Number
After starting the game, the user is prompted to guess a number between 1 and 100.
Enter an integer as a guess when prompted.
3.3 Feedback on Guesses
After each guess, the game provides feedback to the user:
If the guess is too high, the game informs the user that their guess is too high.
If the guess is too low, the game informs the user that their guess is too low.
If the guess is correct, the game congratulates the user and displays the correct number.
3.4 End of the Game
The game ends when the user guesses the correct number or runs out of attempts.
If the user guesses the correct number, the game displays a congratulatory message.
If the user runs out of attempts, the game informs the user that they have exhausted their attempts and displays the correct number.
4. Dependencies
The Number Guessing Game program does not have any external dependencies. It utilizes only the standard Java libraries for input/output operations and random number generation.
5. Error Handling
The game validates user input to ensure it is a valid integer. If the user enters invalid input, they are prompted to enter a valid integer.
If the user attempts to guess a number outside the valid range of 1 to 100, they are prompted to enter a valid guess.
6. Example
Suppose the randomly generated number is 47:

The user launches the program.
The game prompts the user to guess a number between 1 and 100.
The user enters their guess, for example, 50.
The game informs the user that their guess is too high.
The user enters another guess, for example, 40.
The game informs the user that their guess is too low.
The user enters their final guess, for example, 47.
The game congratulates the user for guessing the correct number.




