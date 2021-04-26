# Conditional Statements

## 1.) If Statements
#### An "if statement" is written by using the if keyword. The body of if is executed only if this evaluates to True.
```python
my_age = 18

if my_age >= 18 :
    print("You are an adult.")
```

## 2.) If/Else Statements
#### The if..else statement evaluates test expression and will execute the body of if only when the test condition is True.
#### If the condition is False, the body of else is executed. Indentation is used to separate the blocks.

```python
H2o_is_water = True

if H2o_is_water == False:
    print("Wrong Answer")
else:
    print("You are correct")
```

## 3.) If/Else/Elif Statements
#### The elif keyword is pythons way of saying "if the previous conditions were not true, then try this condition".
```python
first_name = "Mike"

if first_name == "John":
    print("Yes,my first name is John")
elif first_name == "Doe":
    print("Yes, my first name is Doe")
else:
    print("Who are you?")
```