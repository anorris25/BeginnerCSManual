# Module 1: Variables and Print


# Variables

## Rules for Naming
* Only use alpha-numeric characters and underscores (A-z, 0-9, and _ )
* Needs to start with a letter or underscore character
* Cannot start with a number
* Are case-sensitive (var, Var and VAR are three different variables)

### Legal variable names:
#### myvar = “Sam”
#### my_var = “Sam”
#### _my_var = “Sam”

### Illegal variable names:
#### 2myvar = “Sam”
#### my-var = “Sam”
#### my var = “Sam”

## **Python has no command for declaring a variable so datatype are automatically assigned**

#### x = 3 -> automatically assumed to be an int
#### y = “Tom” -> automatically assumed to be a string

## **To check the data type assigned to your variable, use the type() function**

#### print(type(x)).  -> <class 'int'>
#### print(type(y))  -> <class ‘str’>

<img src="https://github.com/anorris25/BeginnerCSManual/blob/main/Images/checkDataType.png" alt="app store" width="800"/>

## **To specify the data type of a variable, use casting**

#### x = str(3)  -> the integer is now turned into a string -> ‘3’
#### y = int(‘3’)  -> the string is now turned into a integer -> 3

# Print Statements

#### **print() function allows you to output variables**

### Components: print(object(s), sep=separator, end=end, file=file, flush=flush)

#### x = "Python"
#### y = "is"
#### z = "awesome"

## **Utilizing print systems:**
#### print(x, y, z)   -> Python is awesome -> automatically assumed to use “ “ as separator
#### print(x, y, z, sep=“—“) —> Python—is—awesome -> using “—“ as a separator
#### print(x + “ “ + y + “ “ + “ “ + z)  -> Python is awesome -> can separate variables using “+” as well
#### print(x +y+z) -> Pythonisawesome -> make sure to carefully add separators when using “+”
