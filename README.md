[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15323832&assignment_repo_type=AssignmentRepo)

# SE-Assignment-6

Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

Questions:

1. Python Basics:

   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.

   Python is a high-level, interpreted programming language known for its readability and simplicity. Key features include:

Easy Syntax: Simplifies coding and maintenance.
Versatility: Supports multiple paradigms (procedural, object-oriented, functional).
Extensive Libraries: Rich ecosystem for diverse applications.
Community Support: Strong developer community and resources.
Examples of use cases where Python is particularly effective:

Web Development: Frameworks like Django and Flask.
Data Science and Machine Learning: Libraries such as pandas, NumPy, and TensorFlow.
Automation and Scripting: Tools for automating repetitive tasks.
Scientific Computing: Libraries like SciPy and Matplotlib.

2. Installing Python:

   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.

   Download Python: I go to python.org and download the latest version for Windows.

Run Installer: I execute the downloaded installer. I check "Add Python to PATH" and select "Install Now."

Verify Installation:

I open Command Prompt.
Type python --version and press Enter.
I got the installed Python version.
I install virtualenv:

In Command Prompt, I ran pip install virtualenv.
Set Up Virtual Environment:

I navigated to your project directory: cd path\to\your\project.
Create a virtual environment: python -m venv env.
Activate the virtual environment: .\env\Scripts\activate.

3. Python Syntax and Semantics:

   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.

   print("Hello, World!")
   Basic syntax elements:

   print function: Outputs text to the console.
   Quotation marks ("): Enclose the string to be printed.
   Parentheses (()): Used to pass arguments to the
   function.

4. Data Types and Variables:

   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.

   Basic Data Types in Python:

Integer (int): Whole numbers, e.g., 5
Float (float): Decimal numbers, e.g., 3.14
String (str): Text, e.g., "hello"
Boolean (bool): True/False values, e.g., True
Example Script:

# Creating variables of different data types

age = 25 # int
height = 5.9 # float
name = "Alice" # str
is_student = True # bool

# Using the variables

print(age) # Output: 25
print(height) # Output: 5.9
print(name) # Output: Alice
print(is_student) # Output: True

5. Control Structures:

   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.

   Conditional Statements: Used to execute code based on conditions.

Example if-else Statement:
x = 10
if x > 5:
print("x is greater than 5")
else:
print("x is 5 or less")
Loops: Used to repeat a block of code multiple times.

Example for Loop:
for i in range(3):
print(i)
if-else: Checks a condition and executes corresponding code blocks.
for: Iterates over a sequence or range.

6. Functions in Python:

   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.

   Functions in Python: Reusable blocks of code that perform a specific task. They help in organizing code and reducing redundancy.

Example Function:
def add(a, b):
return a + b

# Calling the function

result = add(3, 5)
print(result) # Output: 8

7. Lists and Dictionaries:

   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.

   Differences:

List: Ordered, indexed, and mutable collection of elements.
Dictionary: Unordered, mutable collection of key-value pairs.
Example Script:

# List of numbers

numbers = [1, 2, 3, 4, 5]
numbers.append(6)
print(numbers) # Output: [1, 2, 3, 4, 5, 6]

# Dictionary with key-value pairs

person = {'name': 'Alice', 'age': 30}
person['age'] = 31
print(person) # Output: {'name': 'Alice', 'age': 31}

8. Exception Handling:

   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.

   Exception Handling in Python: Mechanism to handle runtime errors, allowing the program to continue execution.

Example:
try:
result = 10 / 0
except ZeroDivisionError:
print("Cannot divide by zero")
finally:
print("Execution complete")
try block: Code that may raise an exception.
except block: Code that runs if an exception occurs.
finally block: Code that always runs, regardless of exceptions.

9. Modules and Packages:

   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.

   Modules: Single Python files containing reusable code.
   Packages: Collections of modules in directories with an **init**.py file.

Importing and Using a Module:
import math

result = math.sqrt(16)
print(result) # Output: 4.0
import math: Imports the math module.
math.sqrt(16): Uses the sqrt function from the math module.

10. File I/O:

                - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.

                Reading from a File:
                # Reading from a file

            with open('file.txt', 'r') as f:
            content = f.read()
            print(content)
            Writing to a File:
            # Writing to a file

        data = ['apple', 'banana', 'cherry']
        with open('fruits.txt', 'w') as f:
        for fruit in data:
        f.write(fruit + '\n')
        Reading: Uses open() with mode 'r'.

    Writing: Uses open() with mode 'w'.

# Submission Guidelines:

- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].
