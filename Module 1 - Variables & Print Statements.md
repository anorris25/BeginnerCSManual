# Module 1: Variables and Print Statements


# Variables

## Rules for Naming
* Only use alpha-numeric characters and underscores (A-z, 0-9, and _ )
* Needs to start with a letter or underscore character
* Cannot start with a number
* Are case-sensitive (var, Var and VAR are three different variables)

### Legal variable names:
#### myvar = “Sam”
#### my_var = “Sam”
#### _my_var_ = “Sam”

### Illegal variable names:
#### 7myvar = “Sam”
#### my-var = “Sam”
#### my var = “Sam”

## **Python has no command for declaring a variable so datatype are automatically assigned**

#### x = 3 -> automatically assumed to be an int
#### y = “Tom” -> automatically assumed to be a string

## **To check the data type assigned to your variable, use the type() function**

<img src="https://github.com/anorris25/BeginnerCSManual/blob/main/Images/checkDataType.png" alt="app store" width="800"/>

## **To specify the data type of a variable, use casting**

#### x = str(3)  -> the integer is now turned into a string -> ‘3’
#### y = int(‘3’)  -> the string is now turned into a integer -> 3

<img src="https://github.com/anorris25/BeginnerCSManual/blob/main/Images/casting.png" alt="app store" width="800"/>

# Print Statements

#### **print() function allows you to output variables**

### Components: print(object(s), sep=separator, end=end, file=file, flush=flush)

#### x = "Python"
#### y = "is"
#### z = "awesome"

## **Utilizing print systems:**
#### Automatically assumed to use “ “ as separator
<img src="https://github.com/anorris25/BeginnerCSManual/blob/main/Images/printStatement1.png" alt="app store" width="800"/>

#### Use a different separator(“—“)
<img src="https://github.com/anorris25/BeginnerCSManual/blob/main/Images/printStatement2.png" alt="app store" width="800"/>

#### Can separate variables using “+” as well
<img src="https://github.com/anorris25/BeginnerCSManual/blob/main/Images/printStatement3.png" alt="app store" width="800"/>

#### Carefully add separators when using “+”
<img src="https://github.com/anorris25/BeginnerCSManual/blob/main/Images/printStatement4.png" alt="app store" width="800"/>

# Arrays

### An array is a special variable that can hold more than one value at a time.

#### When you have a list of items instead of making multiple variables like this: 
##### name1 = “Fred”
##### name2 = “George”
##### name3 = “Sally”

#### Solution is to use an array
##### names = [“Fred”, “George”, “Sally”]

#### To access element in array:
##### names[0]   -> this accesses element “Fred”

#### To change element in array:
##### names[0] = “Bob”  -> this allows the first element to now be “Bob” instead of “Fred”
