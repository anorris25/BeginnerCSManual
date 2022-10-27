# Module 4: Functions

## What are Functions?
* Functions are structures that allow us to complete a series of actions in our program. We use them to perform tasks!

<img src="https://github.com/anorris25/BeginnerCSManual/blob/6f537e6819dc8450cce30b641506e9cc84ad3460/Images/do_something.png" alt="do_something function" width="800"/>

## Types of Functions:
1. __Built-in functions:__ functions that Python provides for us like __print()__ and __input__!
* Take a look at https://docs.python.org/3/library/functions.html to see all of Python's built-in functions. Scroll down to see what they do!
3. __User-defined functions:__ functions that programmers create to accomplish specific tasks in their program.

## Function Structure

Let's analyze our "do_something()" function from before:

<img src="https://github.com/anorris25/BeginnerCSManual/blob/6f537e6819dc8450cce30b641506e9cc84ad3460/Images/do_something_labeled.png" alt="do_something function labeled" width="800"/>

1. Every function in Python starts with __def__, followed by the __function name__, and __():__
* "Parameters" are optional inputs that the function uses and changes. Parameters go __inside__ the parentheses. (more on that later)
  * _def makeTable():_, _def greet(name):_, and _def add(num1, num2):_ are all valid first lines of a user-defined function.

2. Every function also contains a body
* This is where we add statements to complete our tasks
* In the do_something() function, our body completes 3 tasks:
  * prints "Look I'm doing something"
  * prints 5 *s
  * prints "Look I'm doing more!!!"

3. To call a function, simply write the function name followed by parentheses. If the function takes parameters, put them _inside_ the parentheses.
* _makeTable()_, _greet("John")_, and _add(x, y)_ are all valid function calls.
* Do NOT put a function call within the function definition! This may result in an infinite loop.
  * In later programming courses you will learn how to do this properly. It's called _recursion_!

## Let's take a look at another example (with parameters!):

<img src="https://github.com/anorris25/BeginnerCSManual/blob/6f537e6819dc8450cce30b641506e9cc84ad3460/Images/add.png" alt="add" width="800"/>

This add function takes in two parameters (num1, and num2).
* num1 and num2 reserve spots for numbers or variables that contain numbers!
* This function _returns_ the sum of num1 and num2.

Notice that unlike do_something(), add(num1, num2) prints nothing to the console!
* This is because the do_something() function prints within the function.
* In order to see if our add function is working properly, we can call the function within a print statement!

<img src="https://github.com/anorris25/BeginnerCSManual/blob/6f537e6819dc8450cce30b641506e9cc84ad3460/Images/print_add.png" alt="printing add" width="800"/>

## User Input!

When programs need the user to provide information, it takes in _user input_. Here, we will learn how to use the built-in Python function _input()_ to store what the user provides for us.

Below is the definition of a "greet" function that asks the user for their name and says "Hello * user name * , how are you?":

<img src="https://github.com/anorris25/BeginnerCSManual/blob/6f537e6819dc8450cce30b641506e9cc84ad3460/Images/greet.png" alt="define greet()" width="800"/>

<img src="https://github.com/anorris25/BeginnerCSManual/blob/6f537e6819dc8450cce30b641506e9cc84ad3460/Images/greet2.png" alt="greeting prompt" width="800"/>

<img src="https://github.com/anorris25/BeginnerCSManual/blob/6f537e6819dc8450cce30b641506e9cc84ad3460/Images/greet3.png" alt="user input" width="800"/>

<img src="https://github.com/anorris25/BeginnerCSManual/blob/6f537e6819dc8450cce30b641506e9cc84ad3460/Images/greet4.png" alt="greeting" width="800"/>









