Basic Calculator Program

    This is a simple calculator program written in Python. It allows users to perform basic arithmetic operations: addition, subtraction, multiplication, and division. The program also includes an option to restart the calculator after each operation or exit entirely.

    Features
    Addition
    Subtraction
    Multiplication
    Division
    Exit Program
    How It Works
    
    The program starts by displaying a menu with five options:
    
    1. Add
    2. Subtract
    3. Multiply
    4. Divide
    5. Exit
    
    The user selects an option by entering the corresponding number.
    
    If an invalid option (number outside 1-5) is entered, the program automatically exits and displays an "Invalid number" message.
    If the user selects any operation between 1 and 4, the program prompts for two numbers, which are then used in the chosen calculation.
    
    Result Display: The result of the operation is displayed in the console.
    
    Repeat or Exit: After showing the result, the user is asked if they want to perform another operation:
    
    Entering y (yes) restarts the program from the beginning.
    Entering n (no) or any other response exits the program.
    Example Usage
    Below is an example of the program’s workflow:
    
    mathematica
    Copiar código
    Selecione uma opção:
    1. Add
    2. Subtract
    3. Multiply
    4. Divide
    5. Exit
    
    Insert the number corresponding to the operation desired: 1
    Instert the first number: 5
    Insert the second number: 3
    The sum of the numbers is: 8
    
    Do you want to perform another operation? (y/n): y
    Functions Explained
    mult(a, b)
    Multiplies two numbers and returns the result.
    
    Parameters:
    a: First number (float or integer).
    b: Second number (float or integer).
    Returns: Product of a and b.
    div(a, b)
    Divides two numbers and returns the result.
    
    Parameters:
    a: First number (float or integer).
    b: Second number (float or integer). Should not be zero to avoid division errors.
    Returns: Quotient of a and b.
    main()
    The main function that provides the user interface for the calculator.
    
    Displays options for the user and performs the desired calculation.
    Handles restarting or closing the program based on user input.
    Notes
    The program automatically exits if the user selects option 5 or an invalid operation.
    quit() is used to stop the program when the user chooses to exit.
