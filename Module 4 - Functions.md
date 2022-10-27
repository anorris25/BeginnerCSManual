# Module 4: Functions

## Before you begin:
Follow along! We are going to be using a free online compiler called Programiz for all of our programs. Link: https://www.programiz.com/python-programming/online-compiler/
Programiz Guide:




## What are Functions?
* Functions are structures that allow us to complete a series of actions in our program. We use them to perform tasks!
* Example (read the comments!):

<img src="https://github.com/anorris25/BeginnerCSManual/blob/6f537e6819dc8450cce30b641506e9cc84ad3460/Images/do_something.png" alt="do_something function" width="800"/>

## Types of Functions:
1. __Built-in functions:__ functions that Python provides for us like __print()__ and __input()__!
* Take a look at https://docs.python.org/3/library/functions.html to see all of Python's built-in functions. Scroll down to see what they do!
3. __User-defined functions:__ functions that programmers create to accomplish specific tasks in their program.

## Function Structure:

Let's analyze our "do_something()" function from before:

<img src="https://github.com/anorris25/BeginnerCSManual/blob/6f537e6819dc8450cce30b641506e9cc84ad3460/Images/do_something_labeled.png" alt="do_something function labeled" width="800"/>

1. Every function in Python starts with __def__, followed by the __function name__, and __():__
* "Parameters" are optional inputs that the function uses and changes. Parameters go __inside__ the parentheses. (more on that later)
  * _def makeTable():_, _def greet(name):_, and _def add(num1, num2):_ are all valid first lines of a user-defined function.

2. Every function also contains a body.
* This is where we add statements to complete our tasks
* In the do_something() function, our body completes 3 tasks:
  * prints "Look I'm doing something"
  * prints 5 *s
  * prints "Look I'm doing more!!!"

3. Calling a function causes the function body to execute. To call a function, simply write the function name followed by parentheses. If the function takes parameters, put them _inside_ the parentheses.
* _makeTable()_, _greet("John")_, and _add(x, y)_ are all valid function calls.

## Let's take a look at another example (with parameters!):

<img src="https://github.com/anorris25/BeginnerCSManual/blob/6f537e6819dc8450cce30b641506e9cc84ad3460/Images/add.png" alt="add" width="800"/>

This add function takes in two parameters (num1, and num2).
* num1 and num2 reserve spots for numbers or variables that contain numbers!
* This function _returns_ the sum of num1 and num2.

Notice that unlike do_something(), add(num1, num2) prints nothing to the console!
* This is because the do_something() function prints within the function.
* In order to see if our add function is working properly, we can call the function within a print statement!

<img src="https://github.com/anorris25/BeginnerCSManual/blob/6f537e6819dc8450cce30b641506e9cc84ad3460/Images/print_add.png" alt="printing add" width="800"/>

## User Input!:

When programs need the user to provide information, it takes in _user input_. Here, we will learn how to use the built-in Python function _input()_ to store what the user provides for us.

Below is the definition of a "greet" function that asks the user for their name and says "Hello * user name * , how are you?":

<img src="https://github.com/anorris25/BeginnerCSManual/blob/655439bd4edbefed60aca3dd33ad3e4a138b3ae2/Images/greet.png" alt="define greet()" width="800"/>

Inside of input(), we pass a prompt. This prompt shown to the user before they provide their input. We typically choose prompts that tell the user what they are supposed to do. This is what you should see when your program runs:

<img src="https://github.com/anorris25/BeginnerCSManual/blob/655439bd4edbefed60aca3dd33ad3e4a138b3ae2/Images/greet2.png" alt="greet prompt" width="800"/>

The computer is asking for your name! Do you see the cursor on the console? Write your name and hit enter!

<img src="https://github.com/anorris25/BeginnerCSManual/blob/655439bd4edbefed60aca3dd33ad3e4a138b3ae2/Images/greet3.png" alt="input name" width="800"/>

What really happens here when you hit enter is whatever you typed to the console is then stored in variable, _name_. Then, our function prints the greeting statement with whatever you entered to the console (see image below). Pretty cool right?

<img src="https://github.com/anorris25/BeginnerCSManual/blob/655439bd4edbefed60aca3dd33ad3e4a138b3ae2/Images/greet4.png" alt="output greet!" width="800"/>

## Challenge Problem: Cats or Dogs

Define a function named cats_or_dogs that takes no parameters. Ask the user "Which is better? cats or dogs: ". If the user inputs "cats", the console should respond with "Meow!". If the user responds with "dogs", the console should respond with "Bark!" If the user inputs something other that "cats" or "dogs", the console should tell them "You can only answer cats or dogs. Try again!", then the prompt appears again.

<img src="https://github.com/anorris25/BeginnerCSManual/blob/81cf8d14ce348c9d32ed972a2989b6f84595ab44/Images/cats_or_dogs.png" alt="empty cats_or_dogs" width="800"/>

### Hints:
* Use conditionals since we are checking for different inputs. If this happens -> then do this
* We use == to determine if two values are the same. Strings are values!

## Solution:

<img src="https://github.com/anorris25/BeginnerCSManual/blob/81cf8d14ce348c9d32ed972a2989b6f84595ab44/Images/func_solution.png" alt="solution to cats_or_dogs" width="800"/>
Don't be intimidated by the code. Read it line by line and try to understand what it's doing!

## Summary:

* In this module, we covered:
  * Functions: built-in & user defined
  * Function Structure
  * Parameters
  * User Input
 
* Hopefully, completing this module helped you understand the significance of functions. Functions are very common and important structures used in programming. We use functions in our programs to do things! What would programs be if they couldn't do things? 








