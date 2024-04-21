
CYK Algorithm for Context-Free Grammar Parsing

•   By: 
   - Ana Sofia Alfonso Moncada
   - David Alejandro Ramírez

•   Overview:
   - This project implements the Cocke-Younger-Kasami (CYK) algorithm for parsing strings based on a given context-free grammar (CFG). The algorithm determines whether a given string can be generated by the CFG. We’ve implemented this algorithm in Python 3.10.

•	Programming Language: 
    Python 3.10

•	Tools: 
   - PyCharm 2023.1.4 
   - GitHub (https://github.com/SofiAlfonso/LFC2_CYK.git) 
   - Dexter C. Kozen, Automata and Computability


•  Understanding the CYK Algorithm Function:
   - The CYK function implements the Cocke-Younger-Kasami (CYK) algorithm.
   - It takes two parameters: G, which represents the grammar rules, and str, which is the string to be evaluated.
   - The function returns "yes" if the string can be generated by the given grammar rules, and "No" otherwise.

•   Input and Output:
   - The Start function handles input and output operations.
   - It prompts the user to input the grammar rules and strings to evaluate.
   - It utilizes the CYK function to determine whether each string is accepted by the grammar.
   - It returns a dictionary containing the strings as keys and their corresponding acceptance status ("yes" or "No") as values.

•  Instructions to run the Program:
   -  Execute the Python script in a Python environment.
   -  Input the number of test cases.
   -  For each test case input the number of non-terminal symbols and the number of strings to evaluate, also the rules of the grammar and the strings you want to evaluate.
   -  Example:
   -  Input:
   - 2                   # Number of test cases
   - 2 1                 # Number of non-terminal symbols and strings to evaluate for test case 1
   - S AB BC             # Grammar rules for test case 1
   - A a
   - B b
   - C c
   - abc                 # String to evaluate for test case 1
   - 1 1                 # Number of non-terminal symbols and strings to evaluate for test case 2
   - S AB BC             # Grammar rules for test case 2
   - A a
   - B b
   - C c
   - xyz                 # String to evaluate for test case 2
    
•   Output:
   -  abc -> yes          # Result for test case 1: The string "abc" can be generated by the given grammar.
   -  xyz -> No           # Result for test case 2: The string "xyz" cannot be generated by the given grammar.
