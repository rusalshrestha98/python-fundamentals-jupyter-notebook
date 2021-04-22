# Variables

## 1.) Creating a Variable
### A variable is a reserved memory location for storing values. Python has no command for declaring a variable.  Instead, a variable is created the moment you first a  ssign a value to it.

```python
x = 5
y = "John"
print(x)
print(y)
```
### Variables do not need to be declared with any particular type, and can even change type after they have been set.

```python
x = 4
x = "Sally"  
print(x)
```

## 2.) Casting
### Type Casting is the method to convert the variable data type into a certain data type in order to the operation required to be performed by users.
### There can be two types of Type Casting in Python:
* Implicit Type Casting: automatically performed by the Python interpreter.
```python
# Python automatically converts a to int 
a = 7
print(type(a)) 
```
* Explicit Type Casting: also called Type Casting, the data types of objects are converted using predefined functions by the user.
```python
x = str(3)    # x will be '3'
y = int(3)    # y will be 3
z = float(3)  # z will be 3.0
```

## 3.) Getting the Data Type
### You can get the data type of a variable with the type() function.
```python
x = 5
y = "John"
print(type(x))
print(type(y))
```

## 4.) Quotes
### String variables can be declared either by using single or double quotes:
```python
x = "Hello World!"
# is the same as
x = 'Hello World!'
```

## 5.) Case Sensitive
### Variable names are case-sensitive.
```python
a = 4
A = "Sally"
#A will not overwrite a
```

## 6.) Variable Names
### A variable can have a short name (like x and y) or a more descriptive name (age, carname, total_volume). Rules for Python variables:
* A variable name must start with a letter or the underscore character
* A variable name cannot start with a number
* A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ )
* Variable names are case-sensitive (age, Age and AGE are three different variables)
### Examples of variable names that are allowed:
```python
myvar = "John"
my_var = "John"
_my_var = "John"
myVar = "John"
MYVAR = "John"
myvar2 = "John"
```
### Examples of variable names that are not allowed:
```python
2myvar = "John"
my-var = "John"
my var = "John"
```

## 7.) Variable Naming Conventions
### Variable names with more than one word can be difficult to read.There are several techniques you can use to make them more readable:
* Camel Case: each word, except the first, starts with a capital letter
```python
myVariableName = "John"
```
* Pascal Case: each word starts with a capital letter
```python
MyVariableName = "John"
```
* Snake Case: each word is separated by an underscore character
```python
my_variable_name = "John"
```

## 8.) Assigning Multiple Values
### Python allows you to assign muliple values to mulple variables in the same line. Follow the example below: 
```python
x, y, z = "Orange", "Banana", "Cherry"
print(x)
print(y)
print(z)
```

## 9.) One Value to Multiple Variables
### Python allows you to assign teh same value to multiple variables in the same line. Follow the example below: 
```python
x = y = z = "Orange"
print(x)
print(y)
print(z)
```

## 10.) Unpack a Collection
### If you have a collection of values in a list, tuple etc. Python allows you extract the values into variables. This is called unpacking.
```python
fruits = ["apple", "banana", "cherry"]
x, y, z = fruits
print(x)
print(y)
print(z)
```

## 9.) Global Variables
### Variables that are created outside of a function (as in all of the examples above) are known as global variables. Global variables can be used by everyone, both inside of functions and outside.
```python
x = "awesome"

def myfunc():
  print("Python is " + x)

myfunc()
```