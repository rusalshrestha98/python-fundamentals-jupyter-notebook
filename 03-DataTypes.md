# Data Types

## 1.) Strings
#### String is wrapped in either single quotaion marks or double quotation marks.
##### For example: 
``` Python
("Hello") is the same as ('Hello')
```
#### You can assign string to a variable:
```Python
x = "Hello World"
print (x)
```
##### Result
```Python
Hello World
```

### **_MultiLine String_**
#### You can assign multiline string to a variable by using three quotation marks. (Again, both single quotation marks and double quotation mark work as long as the opening quotarion mark is the same as the ending quotation mark)
##### For example:
```Python
x = """Lorem ipsum dolor sit amet,
consectetur adipiscing elit,
sed do eiusmod tempor incididunt
ut labore et dolore magna aliqua."""
print (x)
```
##### Result
```Python
Lorem ipsum dolor sit amet,
consectetur adipiscing elit,
sed do eiusmod tempor incididunt
ut labore et dolore magna aliqua.
```  

### **_Loop through a String_**
#### If you want to loop through a String, we will use a **for** loop (which we will cover in Chapter 6)  

##### Example:
```Python
for x in "apple":
    print (x)
```
##### Result
```Python
a
p
p
l
e
```

### **_String Concatenation_**
#### To combin two Strings, you can use **+** operator.
##### Example:
```Python
a = "Good "
b = "Morning"
c = "!"
d = a + b + c
print (d)
```
##### Result:
```Python
Good Morning!
```

## **_String Method_**

### 1- capitalize( ): Convert the 1st character to upper case. 
##### Example:
```Python
text = "good night!"
capitalizedText = text.capitalize()
print (capitalizedText)
```
##### Result:
```Python 
Good night!
```

### 2- find( ): Search the string for a specified value and returns the position of where it was found. 
##### Example:
```Python
text = "You are beautiful."
x = text.find("are")
print (x)
```
##### Result:
```Python 
4
```

### 3- lower( ): Converts a string into lower case. 
##### Example:
```Python
text = "Hello my FRIENDS"
x = text.lower()
print (x)
```
##### Result:
```Python 
hello my friends
```

### 4- replace( ): Returns a string where a specified value is replaced with a specified value. 
##### Example:
```Python
text = "Good afternoon!"
x = text.replace("afternoon", "morning")
print (x)
```
##### Result:
```Python 
Good morning!
```

### 5- swapcase( ): Swaps cases, lower case becomes upper case and vice versa. 
##### Example:
```Python
text = "Have a Good DaY"
x = text.swapcase()
print (x)
```
##### Result:
```Python 
hAVE A gOOD dAy
```

## 2.) Integers
#### Short form: Int
#### Integer is a whole number, positive or negative, without decimals, of unlimited length
##### Example of Integers:
```Python
x = 10
y = -53
z = 154638294742
a = -477639928888398
```

## 3.) Float
#### Float is a floating point number, is a number, positive or negative, containing one or more decimals.
##### Example of Float:
```Python
x = 1.50
y = -3.5
z = 10.0
a = -49.0
```

## 4.) Boolean
#### Booleans represent one of two values: True or False.
##### Example:
```Python
print (10 > 1)
print (2 == 2)
print (5 < 3)
```
##### Result:
```Python
True
True
False
```

## 5.) Lists
#### Lists are used to store multiple items in a single variable.
#### A list uses brucket. [ ]
#### Lists are mutable.
#### Lists allow duplicates
#### List items can be of any data type.
#### A list can contain different data type.
##### Example of a list:
```Python
exampleList = ["apple", "orange", "banana", "lemon", "orange", 1, -0.6, False]
```
### **_List length_**
#### For knowing the length of a list, use **len()**
##### Example:
```Python
exampleList = ["apple", "orange", "banana", "lemon", "orange"]
print (len(exampleList))
```
##### Result
```Python
5
```

## 6.) Tuples
#### Tuples are written with round brackets ( )
#### A tuple is unchangeable.
#### Tuples allow duplicates
#### Tuple items can be of any data type.
#### Tuples can contain different data type.
##### Example of a tuple:
```Python
exampleTuple = ("male", "female", "boy", "girl", "boy")
```

## 7.) Dictionary
#### Dictionaries are used to store data values in key:value pairs.
#### A dictionary is a collection which is ordered*, changeable and does not allow duplicates.
#### Dictionaries are written with curly brackets, and have keys and values. { }
```Python
exampleDict = {"brand": "Tesla", "year": 2019, "color": "white"}
```