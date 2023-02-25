# **Python**

![Python Logo](https://www.python.org/static/community_logos/python-logo-generic.svg "Python Logo")

# Table of Contents
1. [Python Introduction](#python-introduction)
2. [Python Getting Started](#python-getting-started)
3. [Python Syntax](#python-syntax)
4. [Python Comments](#python-comments)
5. [Python Variables](#variables)

# References
1. [python.org](https://www.python.org/ "python.org")
2. [PEP 0 – Index of Python Enhancement Proposals (PEPs)](https://peps.python.org/pep-0000/ "PEP 0 – Index of Python Enhancement Proposals (PEPs)")
3. [PEP 8 – Style Guide for Python Code](https://peps.python.org/pep-0008/#introduction "PEP 8 – Style Guide for Python Code")
4. [W3 Schools Python Introduction](https://www.w3schools.com/python/python_intro.asp "python introduction")

# Python Tutorial

## Python Introduction

### What is Python?

Python is a popular programming language. It was created by Guido van Rossum, and released in 1991.

It is used for:
* web development(server-side)
* software development
* mathematics
* system scripting

### What can Python do?
* Python can be used on a server to create web applications
* Python can be used alongside software to create workflows
* Python can connect to database systems. It can also read and modify files.
* Python can be used to handle big data and perform complex mathematics
* Python can be used for rapid prototyping, or for production-ready software development

### Why Python?
* Python works on different platforms (Windows, Mac, Linux, Raspberry Pi, etc)
* Python has a simple syntax similar to the English language
* Python has syntax that allows developers to write programs with fewer lines than some other programming languages
* Python runs on an interpreter system, meaning that code can be executed as soon as it is written. This means that prototyping can be very quick.
* Python can be treated in procedural way, an object-oriented way or a functional way.

### Good to know
* The most recent major version of Python is Python 3, which shall be used in this tutorial. However, Python 2, although not being updated with anything other than security updates, is still quite popular.
* In this tutorial Python will be written in a text editor. It is possible to write Python in an Integrated Development Environment, such as Thonny, Pycharm, Netbeans or Eclipse which are particularly useful when managing larger collections of Python files.

### Python Syntax compared to other programming languages
* Python was designed for readability, and has some similarities to the English language with influence from mathematics
* Python relies on indentation, using whitespace, to define scope; such as the scope of loops, functions and classes. Other programming languages often use curly-brackets for this purpose.

---

## Python Getting Started

### Python Install

Many PCs and Macs will have python already installed.
To check if you have python installed on a Windows PC, search in the start bar Python or run the following on the Command Line (cmd.exe):

>C:\Users\\*Your Name*>python --version

To check if you have python installed on a Linux or Mac, then on linux open the command line or on Mac open the Terminal and type:

>python --version

If you find that you do not have Python installed on your computer, then you can download it for free from the following website: https://www.python.org/

### Python Quickstart

Python is an interpreted programming language, this means that as a developer you write Python (.py) files in a text editor and then put those files into the python interpreter to be executed.

The way to run a python file is like this on the command line:

>C:\Users\\*Your Name*>python helloworld.py

Where "helloworld.py" is the name of your python file.

Let's write our first Python file, called helloworld.py, which can be done in any text editor.

```python
print("Hello, World!")
```

Navigate to the directory where the file is saved, and run:
>python helloworld.py

The output should read:
>Hello, World!

### The Python Command Line

To test a short amount of code in python, sometimes it is quickest and easiest not to write the code in a file. This is made possible because Python can run as a command line itself.

Type the following on the Windows, Mac or Linux command line:

>python

Or, if the "python" command did not work, you can try "py":

>py

From there you can write any python including the hello world example from earlier in the tutorial:

>\>>> print("Hello, World!")

Which will write "Hello, World!" in the command line:

>Hello, World!

Whenever you are done in the python command line, you can simply type the following to quit the python command line interface:

>exit()

---

## Python Syntax

### Execute Python Syntax

As we learned in the previous page, Python syntax can be executed by writing directly in the Command Line:

>\>>>print("Hello, World!") \
> Hello, World!

Or by creating a python file on the server, using the .py file extension, and running it in the Command Line:

>C:\Users\\*Your Name*>python myfile.py

### Python Indentation

Indentation refers to the spaces at the beginning of a code line.

Where in other programming languages in the indentation in code in for readability only, the indentation in Python is very important.

Python uses indentation to indicate a block of code.

```python
if 5 > 2:
    print("Five is greater than two!")
```

Python will give you an error if you skip the indentation

The number of spaces is up to you as a programmer, the most common use is four, but it has to be at least one.

You have to use the same number of spaces in the same block of code, otherwise Python will give you an error:

### Python Variables

In python, variables are created when you assign a value to it:

```python
x = 5
y = "Hello, World!"
```

Python has no command for declaring a variable.

### Comments

Python has commenting capability for the purpose of in-code documentation.

Comments start with a #, and Python will render the rest of the line as a comment"

```python
#This is a comment.
print("Hello, World!")
```

---

## **Python Comments**

Comments can be used to explain Python code.

Comments can be used to make the code more readable.

Comments can be used to prevent execution when testing code.

### Creating a Comment

Comments start with a #, and Python will ignore them:

```python
#This is a comment
print("Hello, World!")
```

Comments can be placed at the end of a line, and Python will ignore the rest of the line:

```python
print("Hello, World!") #This is a comment
```

A comment does not have to be text explains the code, it can also be used to prevent Python from executing code:
```python
#print("Hello, World!")
print("Cheers, Mate!")
```

### Multi Line Comments

Python does not really have a syntax for multi line comments.

To add a multiline comment you could insert a <span style="color:skyblue">#</span> for each line:

```python
#This is a comment
#written in
#more than just one line
print("Hello, World!")
```

Or, not quite as intended, you can use a multiline string.

Since Python will ignore string literals that are not assigned to a variable, you can add a multiline string (triple quotes) in your code, and place your comment inside it:

```python
"""
This is a comment
written in
more than just one line
"""
print("Hello, World!")
```

As long as the string is not assigned to a variable, Python will read the code, but then ignore it, and you have made a multiline comment.

- - -

## **Variables**

Variables are containers for storing data values.

### Creating Variables

Python has no command for declaring a variable.

A variable is created the moment you first assign a value to it.

Variables do not need to be declared with any particular type, and can even change type after they have been set.

```python
x = 4       # x is of type int
x = "Sally" # x is now of type str
print(x)
```

### Casting

If you want to specify the data type of a variable, this can be done with casting.

```python
x = str(3)    # x will be '3'
y = int(3)    # y will be 3
z = float(3)  # z will be 3.0
```
### Get the Type

You can get the data type of a variable with the type() function.

```python
x = 5
y = "John"
print(type(x))
print(type(y))
```

String variables can be declared either by using single or double quotes:

Variable names are case-sensitive.

---

## **Python Variable Names**

### Variable Names

A variable can have a short name (like x and y) or a more descriptive name (age, carname, total_volume). Rules for Python variables:
* A variable name must start with a letter or the underscore character
* A variable name cannot start with a number
* A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ )
* Variable names are case-sensitive (age, Age and AGE are three different variables)

### Multi Words Variable Names

Variable names with more than one word can be difficult to read.

There are several techniques you can use to make them more readable:

**Camel Case**

Each word, except the first, starts with a capital letter:

```python
myVariableName = "John"
```

**Pascal Case**

Each word starts with a capital letter:

```python
MyVariableName = "John"
```

**Snake Case**

Each word is separated by an underscore character:

```python
my_variable_name = "John"
```

---

## **Python Variables - Assign Multiple Values**

### Many Values to Multiple Variables

Python allows you to assign values to multiple variables in one line:

```python
x, y, z = "Orange", "Banana", "Cherry"
print(x)
print(y)
print(z)
```

<mark style="background-color:lightyellow">Note: Make sure the number of variables matches the number of values, or else you will get an error.</mark>

### One Value to Multiple Variables

and you can assign the same value to multiple variables in one line:

```python
x = y = z = "0range"
print(x)
print(y)
print(z)
```

### Unpack a Collection

If you have a collection of values in a list, tuple etc. Python allows you to extract the values into variables.

This is called *unpacking*.

```python
fruits = ["apple", "banana", "cherry"]
x, y, z = fruits
print(x)
print(y)
print(z)
```

---

## Output Variables

The Python print() function is often used to output variables.

```python
x = "Python is awesome"
print(x)
```

In the print() function, you output multiple variables, separated by a comma:

```python
x = "Python"
y = "is"
z = "awesome"
print(x, y, z)
```

You can also use the + operator to output multiple variables:

```python
x = "Python "
y = "is "
z = "awesome"
print(x + y + z)
```

<mark style="background-color:lightyellow">Note: the space character after "Python" and "is ", without them the result would be "Pythonisawesome".</mark>

For numbers, the + character works as a mathematical operator:

```python
x = 5
y = 10
print(x + y)
```

In the print() function, when you try to combine a string and a number with the + operator, Python will give you an error.

The best way to output multiple variables in the print() function is to separate them with commas, which even support different data types:

```python
x = 5
y = "John"
print(x, y)
```

---

## Global Variables

Variables that are created outside of a function (as in all the examples above) are known as global variables.

Global variables can be used by everyone, both inside of functions and outside.

```python
x = "awesome"

def myfunc():
    print("Python is " + x)

myfunc()
```

If you create a variable with the same name inside a function, this variable will be local, and can only be used inside the function. The global variable with the same name will remain as it was, global and with the original value.

```python
x = "awesome"

def myfunc():
    x = "fantastic"
    print("Python is " + x)

myfunc()

print("Python is " + x)
```

### The global Keyword

Normally, when you create a variable inside a function, that variable is local, and can only be used inside that function.

To create a global variable inside a function, you can use a <span style="color:skyblue">global</span> keyword.

If you use the <span style="color:skyblue">global</span>, the variable belongs to the global scope:

```python
def myfunc():
    global x
    x = "fantastic"

myfunc()

print("Python is " + x)
```

Also, use the <span style="color:skyblue">global</span> keyword if you want to change a global variable inside a function.

To change the value of a global variable inside a function, refer to the variable by using the <span style="color:skyblue">global</span> keyword:

```python
x = "awesome"

def myfunc():
    global x
    x = "fantastic"

myfunc()

print("Python is " + x)
```

<!--Come back here to add color to things-->

## **Date Types**

### Built-in Data Types

In programming, data type is an important concent.

Variables can store data of different types, and different types can do different things.

Python has the following data types built-in by default, in these categories:

* Test Type: str
* Numeric Types: int, float, complex
* Sequence Types: list, tuple, range
* Mapping Type: dict
* Set Types: set, frozenset
* Boolean Type: bool
* Binary Types: bytes, bytearray, memoryview
* None Type: Nonetype

### Getting the Data Type

You can get the data type of any object by using the type() function:

Print the data type of the variable x:
```python
x = 5
print(type(x))
```

### Setting the Data Type

In Python, the data type is set when you assign a value to a variable:

|Example|Data Type|
|-|-|
|x = "Hello World"	| str |
|x = 20 |	int	|
|x = 20.5|	float	|
|x = 1j	|complex	|
|x = ["apple", "banana", "cherry"]	|list|	
|x = ("apple", "banana", "cherry")	|tuple	|
|x = range(6)|range|	
|x = {"name" : "John", "age" : 36}|	dict	|
|x = {"apple", "banana", "cherry"}|	set	|
|x = frozenset({"apple", "banana", "cherry"})|	frozenset	|
|x = True|	bool	|
|x = b"Hello"|	bytes	|
|x = bytearray(5)|	bytearray	|
|x = memoryview(bytes(5))|	memoryview	|
|x = None|	NoneType|

### Setting the Specific Data Type

|Example|Data Type|
|-|-|
|x = str("Hello World")	|str	|
|x = int(20)	|int	|
|x = float(20.5)	|float	|
|x = complex(1j)	|complex	|
|x = list(("apple", "banana", "cherry"))	|list	|
|x = tuple(("apple", "banana", "cherry"))|	tuple	|
|x = range(6)	|range	|
|x = dict(name="John", age=36)|	dict	|
|x = set(("apple", "banana", "cherry"))	|set	|
|x = frozenset(("apple", "banana", "cherry"))|	frozenset	|
|x = bool(5)	|bool	|
|x = bytes(5)	|bytes	|
|x = bytearray(5)	|bytearray	|
|x = memoryview(bytes(5))	|memoryview|

## **Numbers**

### Numbers

There are three numeric types in Python:
* int
* float
* complex

Variables of numeric types are created when you assign a value to them:
```python
x = 1 # int
y = 2.8 # float
z = 1j # complex
```

To verify the type of any object in Python, use type() function:

```python
print(type(x))
print(type(y))
print(type(z))
```
### Int

Int, or integer, is a whole number, positive or negative, without decimals, of unlimited length

```python
x = 1
y = 35656222554887711
z = -3255522

print(type(x))
print(type(y))
print(type(z))
```

### Float

Float, or "floating point number" is number, positive or negative, containing one or more decimals

```python
x = 1.10
y = 1.0
z = -35.59

print(type(x))
print(type(y))
print(type(z))
```

Float can can also be scientific numbers with an "e" to indicate the power of 10

```python
x = 35e3
y = 12E4
z = -87.7e100

print(type(x))
print(type(y))
print(type(z))
```

### Complex

Complex numbers are written with a "j" as the imaginary part:

```python
x = 3+5j
y = 5j
z = -5j

print(type(x))
print(type(y))
print(type(z))
```

###Type Conversion

You can convert from one type to another with the int(), float(), and complex() methods:

```python
x = 1    # int
y = 2.8  # float
z = 1j   # complex

#convert from int to float:
a = float(x)

#convert from float to int:
b = int(y)

#convert from int to complex:
c = complex(x)

print(a)
print(b)
print(c)

print(type(a))
print(type(b))
print(type(c))
```

*Note: You cannot convert complex numbers into another number type*

### Random Number

Python does not have a random() function to make a random number, but Python has a built-in module called random that be used to make random numbers:

Import the random module, and display a random number between 1 and 9:
```python
import random
print(random.randrange(1, 10))
```

## **Casting**

### Special a Variable Type

There may be times when you want to specify a type on to a variable. This can be done with casting. Python is an object-oriented languages, and as such it uses classes to define data types, including its primitive types.

Casting in python is therefore done using constructor functions:

* int() - constructs an integer number from an integer literal, a float literal (by removing all decimals), or a string literal (providing the string represents a whole number)
* float() - constructs a float number from an integer literal, a float literal or a string literal (providing the string represents a float or an integer)
* str() - constructs a string from a wide variety of data types, including strings, integer literals and float literals

Integers:
```python
x = int(1)   # x will be 1
y = int(2.8) # y will be 2
z = int("3") # z will be 3
```

Floats:
```python
x = float(1)     # x will be 1.0
y = float(2.8)   # y will be 2.8
z = float("3")   # z will be 3.0
w = float("4.2") # w will be 4.2
```

Strings:
```python
x = str("s1") # x will be 's1'
y = str(2)    # y will be '2'
z = str(3.0)  # z will be '3.0'
```
