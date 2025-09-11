# Using Functions

You've probably heard that the key to great code is automation. In Python, your secret weapon for that is functions! Think of a function like a custom-built tool in your programming toolbox—you create it once to handle a specific job, and then you can use it again and again whenever you need it. No more writing the same boring code over and over!

Ready to see it in action? Let's build a simple function that says hello. It will take a person's name and give them a warm, personal greeting.

Create a file called hello-User-through-functions.py, and paste the following code
~~~
def custom_hello(name):
    print("Hello", name, "!")

custom_hello("Miki")
~~~

## Explaination

### Function Defination
* def: This keyword tells Python that you are defining a new function.
* custom_hello: This is the name of the function. You can call it anything you like, but it's best to use a descriptive name.
* (name): This is the function's parameter. A parameter acts as a placeholder for a piece of data that the function needs to do its job. In this case, the name parameter will hold the name you want to use in the greeting.
* print("Hello", name, "!"): This is the code that runs when the function is called.
* The built-in print() function displays a message on the screen.
* The print() function takes several items, separated by commas. It prints them out with a space between each one by default.
* The code will print the text "Hello", followed by whatever is stored in the name variable, and finally the text "!"

### Function Call

- custom_hello(...): This is how you "call" or execute a function. You use the function's name, followed by parentheses.
- ("Miki"): This is the argument, or the actual value that you pass to the function. When this line is executed, the string "Miki" is assigned to the function's name parameter.