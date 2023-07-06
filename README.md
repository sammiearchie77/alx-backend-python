# 0x00. Python - Variable Annotations

[Python]()[Back-end]()

Resources
Read or watch:

## Python 3 typing documentation

- [MyPy cheat sheet](https://intranet.alxswe.com/rltoken/5j0OtdWh36_HVAHKJX2gaA)
- [Learning Objectives](https://intranet.alxswe.com/rltoken/Eud-nrUG7x3iT6JD2Sas-g)

## General

At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

- Type annotations in Python 3
- How you can use type annotations to specify function signatures and variable types
- Duck typing
- How to validate your code with mypy## Requirements

## General

- Allowed editors: vi, vim, emacs
- All your files will be interpreted/compiled on Ubuntu 18.04 LTS using python3 (version 3.7)
- All your files should end with a new line
- The first line of all your files should be exactly #!/usr/bin/env python3
- A README.md file, at the root of the folder of the project, is mandatory
- Your code should use the pycodestyle style (version 2.5.)
- All your files must be executable
- The length of your files will be tested using wc
- All your modules should have a documentation (python3 -c 'print(__import__("my_module").__doc__)')
- All your classes should have a documentation (python3 -c 'print(__import__("my_module").MyClass.__doc__)')
- All your functions (inside and outside a class) should have a documentation (python3 -c 'print(__import__("my_module").my_function.__doc__)' and python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)')
- A documentation is not a simple word, it’s a real sentence explaining what’s the purpose of the module, class or method (the length of it will be verified)


## To validate your code with mypy, follow these steps:

Step 1: Install mypy (if not already installed)
   - If you haven't installed mypy yet, you can install it using pip (assuming you have Python and pip installed). Open your terminal or command prompt and run the following command:
     ```
     pip install mypy
     ```

Step 2: Create a configuration file (optional)
   - You can create a configuration file called `mypy.ini` or `setup.cfg` in the root directory of your project to configure mypy's behavior. This step is optional, but it allows you to customize mypy's settings. Here's an example of a basic `mypy.ini` file:
     ```
     [mypy]
     python_version = 3.8
     strict = True
     ignore_missing_imports = True
     ```

Step 3: Run mypy on your code
   - Open your terminal or command prompt and navigate to the root directory of your project.
   - Run mypy with the desired options, followed by the path to your code files or directories. For example:
     ```
     mypy path/to/your/code.py
     ```
     You can also specify multiple files or directories separated by spaces.

Step 4: Review the mypy output
   - After running mypy, it will analyze your code and provide output based on its findings. If there are any type errors or inconsistencies, mypy will report them along with the corresponding file and line number.
   - Review the output to identify any potential issues or areas where your code might require modifications to ensure type correctness.

Step 5: Fix type errors
   - Based on the feedback from mypy, make the necessary changes to your code to fix any type errors or inconsistencies.
   - Rerun mypy after making the changes to ensure that the issues have been resolved.

By following these steps, you can use mypy to validate your code and ensure type safety in your Python projects. Remember that mypy performs static type checking, so it can catch many potential errors before your code is even executed.
