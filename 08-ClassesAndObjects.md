# Classes and Objects

## 1.) What are Classes and Objects
#### Python is an object oriented programming language. Unlike procedure oriented programming, where the main emphasis is on functions, object oriented programming stresses on objects.
<p>&nbsp;</p>

#### An object is simply a collection of data (variables) and methods (functions) that act on those data. Similarly, a class is a blueprint for that object.
<p>&nbsp;</p>

#### We can think of class as a sketch (prototype) of a house. It contains all the details about the floors, doors, windows etc. Based on these descriptions we build the house. House is the object.
<p>&nbsp;</p>

#### Just like how homes can be made from a house's blueprint, we can create  objects from a class. An object is also called an instance of a class and the process of creating this object is called instantiation.
<p>&nbsp;</p>

## 2.) Creating a Class
#### Like function definitions begin with the "def" keyword in Python, class definitions begin with a "class" keyword.
```python
class Person:
    "This is a person class"
    age = 10

    def greet(self):
        print('Hello')


# Output: 10
print(Person.age)

# Output: <function Person.greet>
print(Person.greet)

# Output: "This is a person class"
print(Person.__doc__)
```

## 3.) Creating an Object
#### We saw that the class object could be used to access different attributes.

#### It can also be used to create new object instances (instantiation) of that class. The procedure to create an object is similar to a function call.
```python
class Person:
    "This is a person class"
    age = 10

    def greet(self):
        print('Hello')

# create a new object of Person class
harry = Person()

# Output: <function Person.greet>
print(Person.greet)

# Output: <bound method Person.greet of <__main__.Person object>>
print(harry.greet)

# Calling object's greet() method
# Output: Hello
harry.greet()
```
#### This will create a new object instance named harry. We can access the attributes of objects using the object name prefix.

## 4.) Constructors
#### Class functions that begin with double underscore __ are called special functions as they have special meaning.
<p>&nbsp;</p>

#### Of one particular interest is the __init__() function. This special function gets called whenever a new object of that class is instantiated.
<p>&nbsp;</p>

#### This type of function is also called **constructors** in Object Oriented Programming (OOP). We normally use it to initialize all the variables.
<p>&nbsp;</p>

#### In this example, we create a class named Person, and use the **__init__()** funciton to assign values for name and age:
```python
class Person:
  def __init__(self, name, age):
    self.name = name
    self.age = age

p1 = Person("John", 36)

print(p1.name)
print(p1.age)
```

## 5.) Inheritance
#### Inheritance allows us to define a class that inherits all the methods and properties from another class.
* Parent class: is the class being inherited from, also called base class.
* Child class: is the class that inherits from another class, also called derived class.

#### Create a Parent Class
* Any class can be a parent class, so the syntax is the same as creating any other class
```python
class Person:
  def __init__(self, fname, lname):
    self.firstname = fname
    self.lastname = lname

  def printname(self):
    print(self.firstname, self.lastname)
```

#### Create a Child Class
* To create a class that inherits the functionality from another class, send the parent class as a parameter when creating the child class
```python
class Student(Person):
    pass
```
* Now the Student class has the same properties and methods as the Person class.
* Use the Student class to create an object, and then execute the printname method:
```python
x = Student("Mike", "Olsen")
x.printname()
```