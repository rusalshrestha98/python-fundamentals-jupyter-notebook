# Functions

## 1.) What is a Function
#### A function is a block of code which only runs when it is called.

#### You can pass data, known as parameters, into a function.

#### A function can return data as a result.

#### Functions help break our program into smaller and modular chunks. As our program grows larger and larger, functions make it more organized and manageable.

#### Furthermore, it avoids repetition and makes the code reusable.

## 2.) Types of Functions
#### In most programming languages including python, you can divide functions into the following two types:

* Built-in functions - Functions that are built into Python.
* User-defined functions - Functions defined by the users themselves.

## 3.) Creating a Function
### Syntax of a function
```python
def function_name(parameters):
	"""docstring"""
	statement(s)
```
#### Above shown is a function definition that consists of the following components.
* Keyword "def" that marks the start of the function header.
* A function name to uniquely identify the function. Function naming follows the same rules of writing identifiers in Python.
* Parameters (arguments) through which we pass values to a function. They are optional.
* A colon (:) to mark the end of the function header.
* Optional documentation string (docstring) to describe what the function does.
* One or more valid python statements that make up the function body. Statements must have the same indentation level (usually 4 spaces).
* An optional return statement to return a value from the function.

## 4.) Calling a Function
#### To call a function, use the function name followed by parenthesis:
```python
def my_function():
  print("Hello from a function")

my_function())
```

## 5.) Parameters and Arguments
#### The terms parameter and argument can be used for the same thing: information that are passed into a function.

#### From a function's perspective:
* A parameter is the variable listed inside the parentheses in the function definition.
* An argument is the value that is sent to the function when it is called.

#### Arguments are specified after the function name, inside the parentheses. You can add as many arguments as you want, just separate them with a comma.

#### The following example has a function with one argument (fname). When the function is called, we pass along a first name, which is used inside the function to print the full name:
```python
def my_function(fname):
  print(fname + " Refsnes")

my_function("Emil")
my_function("Tobias")
my_function("Linus")
```

## 6.) Keyword Arguments
#### You can also send arguments with the key = value syntax.
#### This way the order of the arguments does not matter.
```python
def my_function(child3, child2, child1):
  print("The youngest child is " + child3)

my_function(child1 = "Emil", child2 = "Tobias", child3 = "Linus")
```

## 7.) Default Parameter Value
#### The following example shows how to use a default parameter value.

#### If we call the function without argument, it uses the default value:
```python
def my_function(name = "Brian"):
  print("My name is " + name)

my_function("Tim")
my_function("Andy")
my_function()
```

## 8.) Passing a List as an Argument
#### You can send any data types of argument to a function (string, number, list, dictionary etc.), and it will be treated as the same data type inside the function.

#### E.g. if you send a List as an argument, it will still be a List when it reaches the function:
```python
def my_function(food):
  for x in food:
    print(x)

fruits = ["apple", "banana", "cherry"]

my_function(fruits)
```

## 9.) Return Values
#### To let a function return a value, use the "return" statement. This will also exit a function and go back to the place from where it was called.
```python
def multiply(x):
  return 3 * x

print(my_function(3))
print(my_function(5))
```
#### If the return statement itself is not present inside a function, then the function will return the "None" object.

## 10.) The "pass" Statement
#### Function definitions cannot be empty, but if you for some reason have a function definition with no content, put in the pass statement to avoid getting an error.
```python
def myfunction():
  pass
```