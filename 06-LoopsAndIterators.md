# Looping and Iterators

## 1.) While Loops
#### With the while loop we can execute a set of statements as long as a condition is true.
```python
counter = 0

while counter < 10:
    print("Hello World!")
    counter = counter + 1

    #Result:  #Hello World!
              #Hello World!
              #Hello World!
              #Hello World!
              #Hello World!
              #Hello World!
              #Hello World!
              #Hello World!
              #Hello World!
```
## 2.) For Loops
#### A for loop is used for iterating over a sequence (that is either a list, a tuple, a dictionary, a set, or a string).

#### This is less like the for keyword in other programming languages, and works more like an iterator method as found in other object-orientated programming languages.

#### With the for loop we can execute a set of statements, once for each item in a list, tuple, set etc.
```python
list_of_accessories = ['Scarf', 'Socks', 'Shoes', 'Belt']

for clothes in list_of_accessories:
     print(clothes)

#Result:  #Scarf
          #Socks
          #Shoes
          #Belt 

```