# Basics

## 1.) Intro
#### What is Python?
* Python is a general-purpose coding language—which means that, unlike HTML, CSS, and JavaScript, it can be used for other types of programming and software development besides web development.

#### What is Python used for?
* Web-Development
* Software Development
* Mathematics
* Machine Learning
* Data Science
* Automation

#### Why Python?
* Works on different platforms (Windows, Mac, Linux, Raspberry Pi, etc).
* Simple syntax similar to the English language.
* Syntax that allows developers to write programs with fewer lines than some other programming languages.
* Large, mature, and active supportive community
* Hundreds of libraries and frameworks
* More efficient, reliable, and faster than most modern languages

#### Good to Know
* The most recent version of Python is Python 3. However, Python 2 is still quite popular.
* You can run Python in you command line, but it probably easiest to run it using a text editor or IDE (Integrated Development Environment) such as Visual Studio Code, PyCharm, etc.

## 2.) Installation
#### Many PCs and Macs will already come with python installed. However, if your machine does not have it available, you can go to https://python.org/downloads/ and follow the instructions for your operating system to get it downloaded on your machine.

## 3.) Pip
#### Pip is the most popular package manager for python. To check if you have pip installed, run the following command.
* Windows:
```python
py -m pip --version
```
* Mac:
```python
py -m pip --version
```

#### If not installed, you can follow the installation documentation for pip at this link: https://pip.pypa.io/en/stable/installing/. 

## 4.) Printing 'Hello World'
#### In this program below, you learn how to create your first python program using the build-in print() function to print the string "Hello World".
```python
print("Hello World!")
```

## 5.) Indentation
#### Indentation refers to the spaces at the beginning of a code line.

#### Where in other programming languages the indentation in code is for readability only, the indentation in Python is very important.

#### Python uses indentation to indicate a block of code.

```python
if 5 > 2:
  print("Five is greater than two!")
```

## 6.) Comments
#### Python has commenting capability for the purpose of in-code documentation.

#### Comments start with a #, and Python will render the rest of the line as a comment:

```python
#This is a comment.
print("Hello, World!")
```