[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15336191&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.

   what is python:
   Python is an interpreted, object-oriented, high-level programming language with dynamic semantics.

   below are the key features of python that make it popular among developers:
    a. Easy to code.
    b. Open source and free softwares.
    c. support for GUI.
    d. Object Oriented Methodology.
    e. High Level Language.
    f. Integrated by Nature.
    g. Extremely Dynamic.

    below are some of the examples of use cases where python is particularly effective.
    a. Game development.
    b. Cloud Computing.
    c. Web Development
    d. Data analysis and Visualization.
    e. Machine learning and Artificial Inteligence.
    f. Automation and Scripting.

2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.
   
   Below are the basic step to follow in order to install python:
   a. Download the Installer by visiting python official website and click on the download button to load the latest version of python.
   b. Run the installer by Locating the downloaded installer file (usually in your Downloads folder) and double-click it to run.
   c. On the installer window, make sure to check the box that says "Add Python to PATH" at the bottom. This is important as it will allow you to use Python from the command line
   d. Click on "Install Now" to begin the installation.

   How to verify the python Installed:
   a. Open the Command Prompt. You can do this by searching for "cmd" in the Start menu and selecting Command Prompt.
   b. In the Command Prompt, type python --version and press Enter. This should display the version of Python you just installed

   To set up a virtual enviroment:
   a. To create a virtual environment, open the Command Prompt and navigate to your project directory.
   b. Run the command python -m virtualvenv ecommerce to create a virtual environment named ecommerce.
   c. Activate the virtual environment by running virtualenv\Scripts\activate (on Windows).

3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.

   single program to print "hello, world":
   below is the basic program to print hello word

   print("Hello, world")

   below is basic syntax element used:
   a. print(): this is an inbuilt python function that output text to the console.
   b. Hello, World: this is a strings, a sequence of character enlose in double quotes. 

4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.

   basic data types in python:
   a. Integers: this is a Whole numbers, positive or negative, without a decimal point example 12, -9.

   b. Floating-Point Numbers: this is a number that contain a decimal point or are written in exponential notation. example 3.3, 0.002

   c. Strings: this is a sequence of characters enclosed in single, double, or triple quotes. exaple "hello"

   d. boolean: this represents one of two values: True or False. examples 'true'

   e. list: this is an ordered collection of items, which can be of different types, enclosed in square brackets.

   short Script:
   Integer
   age = 25
   print(f"Age: {age} (Type: {type(age)})")

   a. Float
   height = 5.9
   print(f"Height: {height} (Type: {type(height)})")

   b. String
   name = "Alice"
   print(f"Name: {name} (Type: {type(name)})")

   c. Boolean
   is_student = True
   print(f"Is Student: {is_student} (Type: {type(is_student)})")

   d. List
   fruits = ["apple", "banana", "cherry"]
   print(f"Fruits: {fruits} (Type: {type(fruits)})")

   e. Tuple
   coordinates = (10.0, 20.0)
   print(f"Coordinates: {coordinates} (Type: {type(coordinates)})")

5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide  examples of an `if-else` statement and a `for` loop.

   loop and conditional statement: 
   Loops and conditional statements are powerful constructs that allow programmers to automate repetitive tasks and control the flow of their programs based on certain conditions

   Example of an 'if-else' statement:

   Example of an if-else statement
   number = 10

   if number > 0:
   print("The number is positive.")
   elif number == 0:
   print("The number is zero.")
   else:
   print("The number is negative.")

   Example of a for loop
   fruits = ["apple", "banana", "cherry"]

   for fruit in fruits:
   print(fruit)

6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.

   Function in python: A function is a block of code which only runs when it is called.

   they are so useful in such a way that In any programming language, functions facilitate code reusability. 

   a python function that takes two argument and return their sum:

   def add_numbers(a, b):
   return a + b

   Example of how to call this function
   result = add_numbers(5, 3)
   print("The sum is:", result)

7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.

   difference between list and dictionaries:
   A list refers to a collection of various index value pairs like that in the case of an array in C++. A dictionary refers to a hashed structure of various pairs of keys and values.

   Scripts that creates a list of number and dictionaries:
   Creating a list of numbers
   numbers = [1, 2, 3, 4, 5]

  Creating a dictionary with key-value pairs
  my_dict = {
   'name': 'John Doe',
   'age': 30,
   'city': 'New York',
   'email': 'john.doe@example.com'
}

   Displaying the initial list and dictionary
  print("Initial list of numbers:", numbers)
  print("Initial dictionary:", my_dict)

 Basic operations on the list
 numbers.append(6)
 numbers.extend([7, 8])
 numbers.remove(3)
 numbers.pop(1)

 Basic operations on the dictionary
 my_dict['age'] = 31
 my_dict['job'] = 'Software Engineer'
 del my_dict['email']

 Displaying the updated list and dictionary
 print("\nUpdated list of numbers:", numbers)
 print("Updated dictionary:", my_dict)

 Accessing elements in list and dictionary
 print("\nAccessing elements:")
 print("Third element in list:", numbers[2])
 print("Name in dictionary:", my_dict['name'])

 Checking length of list and dictionary
 print("\nLengths:")
 print("Length of list:", len(numbers))
 print("Number of keys in dictionary:", len(my_dict))

 Iterating through list and dictionary
 print("\nIterating through list:")
 for num in numbers:
 print(num)

 print("\nIterating through dictionary:")
 for key, value in my_dict.items():
 print(f"{key}: {value}")   

8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.

   Exception Handling: this is a way of handling an error that can cause program to terminate.

   Example of how to use 'try', 'except', and 'finally':
   Example: Handling file operations with try-except-finally blocks

   Function to read and print contents of a file
   def read_file(filename):
   try:
         Attempt to open the file
        with open(filename, 'r') as file:
            content = file.read()
            print("File contents:")
            print(content)
    except FileNotFoundError:
        print(f"Error: The file '{filename}' was not found.")
    except IOError:
        print(f"Error: Failed to read the file '{filename}'.")
    except Exception as e:
        print(f"An unexpected error occurred: {str(e)}")
    finally:
        print("Executing finally block, regardless of exceptions.")

    Testing the function with various scenarios
   if __name__ == "__main__":
      Case 1: Existing file
     read_file("sample.txt")

      Case 2: Non-existing file
      read_file("non_existing_file.txt")

      Case 3: Permission denied (simulate IOError)
      read_file("/etc/shadow")  # This might raise a PermissionError or IOError

      Case 4: No permission to read (simulate PermissionError)
      try:
        read_file("/root/top_secret.txt")
    except PermissionError:
        print("Permission denied to read '/root/top_secret.txt'.")

9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.

   concept of module and packages in python:
    a module is a single file containing Python code, whereas a package is a collection of modules that are organized in a directory hierarchy.

    to import and use module in your scripts You need to use the import keyword along with the desired module name.

    Example: Importing and using the math module

    Importing the math module
    import math

    Using functions from the math module
     print("Value of pi:", math.pi)

     radius = 5
    area = math.pi * radius ** 2
    print("Area of a circle with radius 5:", area)

    angle_in_radians = math.radians(45)
    print("45 degrees in radians:", angle_in_radians)

    sin_value = math.sin(angle_in_radians)
    print("Sine of 45 degrees:", sin_value)

    Using constants and functions directly from math module
    print("Square root of 16:", math.sqrt(16))
   print("Factorial of 5:", math.factorial(5))

10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.

    how to read and write to file in python:
    Reading files: Involves methods ( read() , readline() , readlines() ) to retrieve data from a file. Writing files: Involves methods ( write() , writelines() ) to store data into a file

    Scripts that read a content of a file:
    Script to read the content of a file and print it to the console

   def read_and_print_file(filename):
    try:
        # Attempt to open the file
        with open(filename, 'r') as file:
            content = file.read()
            print(f"Content of the file '{filename}':")
            print(content)
     except FileNotFoundError:
        print(f"Error: The file '{filename}' was not found.")
    except IOError:
        print(f"Error: Failed to read the file '{filename}'.")
    except Exception as e:
        print(f"An unexpected error occurred: {str(e)}")

   Example usage:
    if __name__ == "__main__":
    filename = "sample.txt"  # Replace with your file path
    read_and_print_file(filename)

    script that write content of a file:
    Script to write a list of strings to a file

    def write_list_to_file(filename, content_list):
    try:
        # Attempt to open the file in write mode
        with open(filename, 'w') as file:
            for line in content_list:
                file.write(line + "\n")
        print(f"Successfully wrote {len(content_list)} lines to '{filename}'.")
    except IOError:
        print(f"Error: Failed to write to the file '{filename}'.")
    except Exception as e:
        print(f"An unexpected error occurred: {str(e)}")

   Example usage:
   if __name__ == "__main__":
    filename = "output.txt"  # Replace with your desired output file path
    lines_to_write = [
        "This is line 1",
        "This is line 2",
        "This is line 3"
    ]
    write_list_to_file(filename, lines_to_write)

    refferences:Google, Chatgpt, lesson material, lesson video.

# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


