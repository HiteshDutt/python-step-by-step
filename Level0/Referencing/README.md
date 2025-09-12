# Create and Reuse Modules

In this section let us evaluate, how to create and use resuable components.

## Why do we need re-usable components

Reusable components, as name suggest can be reused. for example, Create a calculator, and add functions like Addition, Subtraction, Multiplication and Division.

Later in our solution assume there plan to create a finance solution where Credit and Debits need to Added or Subracted. Instead of writing this functionality again, let us simply use the function developed for calculator earlier.

## What are we going to do

Creating a file called main.py (could be named anything). This file will act as entry point (for thi example) for other modules to be used.

Before writing content of main.py, let us create other modules. Create a file called module.py

*module.py*
~~~
def hello_from_module(name):
    print("Hello", name, "! From module")
~~~

on main.py add following code

*main.py*
~~~
 import module
 module.hello_from_module("Miki")
~~~

### Explaination of what just happened

*module.py* defines a function, and *main.py* is the script that executes it by importing the module file. This illustrates the fundamental concept of Python modules, which allows you to organize code into reusable files. 

#### module.py
This file acts as a module. A module is a Python file (.py) containing a collection of reusable functions, classes, and variables.

* def hello_from_module(name):: This line defines a function named hello_from_module.
* print(...): The function takes one argument, name, and prints a personalized greeting.

#### main.py

This file is the main program or "script" that will be executed.

* import module: This statement tells the Python interpreter to load the code from the file named module.py. When imported, all functions, classes, and variables defined in module.py are made available to main.py.
* module.hello_from_module("Miki"): This line calls the function hello_from_module.
    - module: This is the namespace of the imported module. You must use this prefix to access its contents.
    - .: This dot operator is used to access the function inside the module namespace.
    - hello_from_module("Miki"): This calls the function with the string "Miki" as the name argument. 

### Execution

~~~
python main.py
~~~
-or-
~~~
python3 main.py
~~~