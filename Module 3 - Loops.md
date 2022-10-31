# Module 3: Loops

## What are Loops?
* Loops are a sequence of instructions that are continually repeated until a certain condition is reached. We can use loops to repeat an instruction multiple times!

<img src="https://github.com/anorris25/BeginnerCSManual/blob/main/Images/Loop%20Example.gif" alt="app store" width="300"/>

## Types of Loops:
1. For Loop
2. While Loop

## Making your own Loops!

Let's make a while loop:

<img src="https://github.com/anorris25/BeginnerCSManual/blob/main/Images/While%20Loop%20Example.png" alt="app store" width="800"/>

1. For a while loop we need a condition to make it stop, meaning when the condition is valid the loop will keep running and will stop once it is no longer valid, in this case when x is less than 5

2. The while loop has a body inside which a command can be carried out when the loop is still running. This allows us to run code repeatedly until the loop stops



Let's make a for loop:

<img src="https://github.com/anorris25/BeginnerCSManual/blob/main/Images/For%20Loop%20Example.png" alt="app store" width="800"/>

1. A for loop is usually used to count numbers, in this case for x in range(5) would make the loop run 5 times. 

2. As with the while loop the body will contain the command to be carried out while the loop is running. 



## Loop Dangers!

**Infinite Loop**
An Infinite Loop is a continuous repetitive conditional loop that gets executed *forever*. Now an infinite loop will not necessarily run forever, it will eventually end when the computer runs out of memory. However, this is something you should avoid becuase your program will hang. 

You can end up in an infinite loop if you don't have a condition that is met in your loop. 

For example:

<img src="https://github.com/anorris25/BeginnerCSManual/blob/main/Images/Infinite%20Loop.png" alt="app store" width="400"/>

In the above image you can see the loop will never exit because *x* will never be less than *-2*