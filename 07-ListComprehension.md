# List Comprehension

## 1.) What is List Comprension?
#### List comprehension is a way to build a new list by applying an expression to each item in an iterable.
<p>&nbsp;</p>

#### Without list comprehension you will have to write a for statement with a conditional test inside:
```python
fruits = ["apple", "banana", "cherry", "kiwi", "mango"]
newlist = []

for x in fruits:
  if "a" in x:
    newlist.append(x)

print(newlist)
```
#### With list comprehension you can do all that with only one line of code:
```python
fruits = ["apple", "banana", "cherry", "kiwi", "mango"]

newlist = [x for x in fruits if "a" in x]

print(newlist)
```
## 2.) Basic Syntax
```python
newlist = [expression for item in iterable if condition == True]
```
* Expression: the current item in the iteration, but it is also the outcome, which you can manipulate before it ends up like a list item in the new list.
* Iterable: can be any iterable object, like a list, tuple, set etc.
* Condition: a filter that only accepts the items that valuate to **True**.

## 3.) Examples
#### Example #1: Set all values in the new list to 'hello'
```python
newlist = ['hello' for x in fruits]
```
#### Example #2: Set the values in the new list to upper case
```python
newlist = [x.upper() for x in fruits]
```
#### Example #3: applies abs() function to all the elements in a list
```python
# Convert list items to absolute values
firstlist = [-4, -2, 0, 2, 4]
newlist = [abs(x) for x in firstlist]
print(newlist)
# Prints [4, 2, 0, 2, 4]
```

#### Example #4: calls a built-in method strip() on each element in a list.
```python
# Remove whitespaces of list items
colors = ['  red', '  green ', 'blue  ']
newlist = [color.strip() for color in colors]
print(newlist)
# Prints ['red', 'green', 'blue']
```