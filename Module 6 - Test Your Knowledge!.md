# Rock, Paper, Scissors!

## Apply the concepts you've learned in modules 1-5 to make a program that plays rock, paper, scissors with the user!

### Step 1
* "import random" into your program. This will allow us to genereate random choices from the computer's side. (We'll see how to use it later)

<img src="https://github.com/anorris25/BeginnerCSManual/blob/b27d8083a833c3c678cdd1bad904b6082f33d509/Images/import_random.png" alt="import random" width="800"/>

### Step 2
* We need to know what the user chose, and what the computer chose. Do not fear, we will show you how to know what the computer "chose".
* First, store what the user chose. We learned how to do this with user input. We'll accept the inputs: "rock", "paper", or "scissors".
* Next, we're going to use our import of "random" to store the computer's choice. Like so:

<img src="https://github.com/anorris25/BeginnerCSManual/blob/cc30c5bf345f57bc66dd3d158eb6cb35dcd0a1c5/Images/random.jpg" alt="Solution" width="800"/>

As you can see, we've made an array of possible actions, and we make the computer randomly choose among those actions.

### Step 3
* The last thing we need to do is compare the user action and computer action and display a tie, win, or lose message.
* Think of all the possible cases. What structures do we use when there are multiple cases?
* Cases:
    * User action is the same as computer action
    * User chooses rock
        * Computer chooses scissors
        * Computer chooses paper
    * User chooses paper
        * Computer chooses rock
        * Computer chooses scissors
    * User chooses scissors
        * Computer chooses paper
        * Computer chooses rock

## Solution:

<img src="https://github.com/anorris25/BeginnerCSManual/blob/b27d8083a833c3c678cdd1bad904b6082f33d509/Images/rps_solution.JPEG" alt="Solution" width="800"/>
