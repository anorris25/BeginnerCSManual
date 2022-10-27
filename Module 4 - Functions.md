# Module 4: Functions

## What are Functions?
* Functions are structures that allow us to complete a series of actions in our program. We use them to perform tasks!

<img src="https://github.com/anorris25/BeginnerCSManual/blob/6f537e6819dc8450cce30b641506e9cc84ad3460/Images/do_something.png" alt="do_something function" width="800"/>

## Types of Functions:
1. __Built-in functions:__ functions that Python provides for us like __print()__!
* Take a look at https://docs.python.org/3/library/functions.html to see all of Python's built-in functions. Scroll down to see what they do!
3. __User-defined functions:__ functions that programmers create to accomplish specific tasks in their program.

## Making your own Functions!

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




