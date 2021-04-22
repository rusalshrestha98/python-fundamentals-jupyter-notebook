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



## 1.) Boolean

## 1.) Lists

## 1.) Tuples

## 1.) Dictionary