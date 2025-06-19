# Simple-Calculator
This project is a simple command-line calculator written in the C programming language. 
It provides a menu-driven interface that allows users to perform six fundamental mathematical operations: addition, subtraction, multiplication, division, modulus, and exponentiation. 
Upon launching the program, users are continuously presented with a numbered menu and can select an operation to perform. 
After selecting an option, the program prompts the user to enter two numeric inputs, performs the chosen calculation, and displays the result formatted to two decimal places.
The calculator is built with a focus on modularity and robustness. Separate functions are defined for operations like division and modulus, each including checks to prevent errors such as division or modulus by zero.
The program also uses the `math.h` library to handle power calculations and to return `NAN` (Not-a-Number) when invalid operations are attempted. Input validation ensures that users cannot proceed with invalid menu choices, and all error messages are printed to the standard error stream to maintain clarity. 
This calculator demonstrates good programming practices in C, such as input handling, modular design, and safe arithmetic operations, making it a reliable and educational example for beginners learning C programming.
