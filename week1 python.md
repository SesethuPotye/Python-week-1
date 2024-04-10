# Python-week-1

""

JUPYTER NOTEBOOK( Interacting with Jupyter Notebook in the browser)

used to write and execute proggraming language
open the app, clieck on new 
In a Jupyter Notebook, new cells can be created by holding down the shift key and pressing enter multiple times.
 To enter Python code, click inside the cell to enter edit mode and start typing.
 To run the code, hold down shift and press enter.

*  PYTHON

*  PYTHON : is a dynamically tpyes, high, interpreted programming language which has easy syntax.
 pyton used for: do almost everything that one can imagine, used for game, development, automation, data anaysis.
 
HOW TO ACCES PYTHON

command prompt, open a terminal and type "Python". Once opened, there are three greater-than symbols indicating that the prompt is ready to accept a line of Python code.
To proceed, type in the command "import this" now. The "import" command is used to fetch a module that can be utilized, and "this" is the name of the module we're importing
Creating and running a simple Python statement, “Hello world!”
name your file: ipynb used for naming your file as an extention in jupyter
python variable: they are created when you are assigning a value to
to access the stored file on python use the "cd" command, which means change directory.on comand prompt

# VARIABLES IN PYTHON(variables in Python,whole numbers; floats, Booleans,)
* A variable is something that is can change, are containers for storing data values.
  
 Creating Variables
* Python has no command for declaring a variable.
* A variable is created the moment you first assign a value to it.

e.g
# x = 5
# y = "John"
# print(x)
# print(y)

to create a variable you need to declear by assigning a value to it

# DATA TYPES

* # interger(int)
* the value can be negative
* but can not be a decimal number
* eg. 1, 4, -7 etc

# FLOAT

* Any number that is a decimal
* can be a negative decimal
* 12.1, -4.3, 1.2

# STRING

* Collaction of different characters 
* Declared by """, etc
* eg "name", "1" etc"

# BOOLEANS

* which is ture or false

  # dictionary:a dictionary is an unordered collection of key-value pairs, where each key is unique and maps to a corresponding value.
* Dictionaries are extremely flexible and versatile data structures that allow for efficient data retrieval and manipulation.
* They are defined using curly braces {} and consist of comma-separated key-value pairs in the format key: value.

example of creating a dictionary..

![image](https://github.com/SesethuPotye/Python-week-1/assets/162969678/b444ddef-ed40-4931-88f3-94b6cb6900ec)
Dictionaries have the following characteristics:

Unordered: Dictionaries do not maintain the order of elements as they are added. The order of key-value pairs in a dictionary is arbitrary and can change between operations. Starting from Python 3.7, the order of insertion of key-value pairs is preserved in dictionaries, but you should not rely on this behavior in older versions of Python.

Mutable: Dictionaries are mutable, meaning you can modify the elements (key-value pairs) after the dictionary is created. You can add, remove, or modify key-value pairs in a dictionary.

Keys are Unique: Each key in a dictionary must be unique. If you try to add a duplicate key, the previous value associated with that key will be overwritten by the new value.

Here are some common operations you can perform with dictionaries in Python:

* Accessing elements by key: value = my_dict[key]
* Adding or updating elements: my_dict[key] = value
* Removing elements: del my_dict[key] or my_dict.pop(key)
* Checking if a key exists: key in my_dict
* Getting the list of keys: my_dict.keys()
* Getting the list of values: my_dict.values()
* Getting the list of key-value pairs: my_dict.items()
* Dictionaries are widely used in Python for various tasks such as storing * * * * configuration settings, representing data records, caching results, mapping values, and more.
*  They provide a convenient and efficient way to organize and manipulate data in Python programs.


DATA STRUCTURES

# list [] 
* are used to store multiple items in a single variable.
* ther are ordered, changeable, and allow duplicate values.
* are indexed, the first item has index [0], the second item has index [1]

  # ordered lists
* When we say that lists are ordered, it means that the items have a defined order, and that order will not change.
* If you add new items to a list, the new items will be placed at the end of the list.

# ALLOWS DUPLICATES
Since lists are indexed, lists can have items with the same value:
 EXAMPLE ODF A LIST[]
 
 * thislist = ["apple", "banana", "cherry", "apple", "cherry"]
*print(thislist)

# List Length
To determine how many items a list has, use the len() function:
EXAMPLE
*thislist = ["apple", "banana", "cherry"]
*print(len(thislist))

# TUPLES()

* Tuple items are ordered, unchangeable, and allow duplicate values.
* Tuple items are indexed, the first item has index [0], the second item has index [1] etc.
  BASICLY TUPLES ARE MORE OF THE SAME AS LIST BUT YOU CAN JUST IDENTIF THE BY ()

# SETS{}

Duplicates Not Allowed
Unchangeable
Unordered
e.g 
* myset = {"apple", "banana", "cherry"}



  


OPERATORS
# Arithmetic Operators:

+: Addition
-: Subtraction
*: Multiplication
/: Division (floating-point division)
//: Floor Division (integer division)
%: Modulus (remainder)
**: Exponentiation

# Comparison Operators:

==: Equal to
!=: Not equal to
<: Less than
>: Greater than
<=: Less than or equal to
>=: Greater than or equal to

# Logical Operators:

and: Logical AND
or: Logical OR
not: Logical NOT
Assignment Operators:

=: Assign value
+=: Add and assign
-=: Subtract and assign
*=: Multiply and assign
/=: Divide and assign
%=: Modulus and assign
//=: Floor division and assign
**=: Exponentiation and assign
&=: Bitwise AND and assign
|=: Bitwise OR and assign
^=: Bitwise XOR and assign
<<=: Left shift and assign
>>=: Right shift and assign

# Membership Operators:

in: Checks if an element exists in a sequence
not in: Checks if an element does not exist in a sequence

# BASIC CONTROL FLOW

*These are conditiona statements
# IF STATEMENT: An "if statement" is written by using the if keyword.

* a = 33
* b = 200
* if b > a:
*  print("b is greater than a")
  
Indentation
*Python relies on indentation (whitespace at the beginning of a line) to define scope in the code, IF THERE IS NO INDENTATION ON THE "IF" STATEMENT THEN THE WILL BE AN ERROR

E.G
* a = 33
* b = 200
* if b > a:
* print("b is greater than a") # you will get an error

# Elif
* The elif keyword is Python's way of saying "if the previous conditions were not true, then try this condition".

* a = 33
* b = 33
* if b > a:
 * print("b is greater than a")
* elif a == b:
*  print("a and b are equal")

#  Else
* The else keyword catches anything which isn't caught by the preceding conditions.

* a = 200
* b = 33
* if b > a:
*  print("b is greater than a")
*elif a == b:
*  print("a and b are equal")
* else:
*  print("a is greater than b")

  # While
  * With the while loop we can execute a set of statements as long as a condition is true.
E.G
 i = 1
while i < 6:
  print(i)
  i += 1( remember to increment i, or else the loop will continue forever.)
 # The break Statement
 * With the break statement we can stop the loop even if the while condition is true:
 * THIS LOOP CAN RUN FOR EVER SO IINORGER FOR YOU TO EXIT THE LOOP YOU NEED TO USE BREAK
E.G 
 * i = 1
* while i < 6:
 * print(i)
 * if i == 3:
*    break
 * i += 1

 * STATEMENT WHICH WILL EXIT THE LOOP AND MOVE ON TO THE NEXT LINE OUTSIED THE CODE

* if you want to skip over certain lines within a loop, you can use the continue statement, which will skip over any lines that come after it and jump back to the top of the loop to start the next iteration.
  
  
  
  










# functions

* A function is a block of code which only runs when it is called.
* You can pass data, known as parameters, into a function.
* A function can return data as a result.
  
# Creating a Function
In Python a function is defined using the def keyword:
e.g def my_function():

Calling a Function
To call a function, use the function name followed by parenthesis:
e.g def my_function():
  print("Hello from a function")

my_function()

# Arguments
* Information can be passed into functions as arguments.
* Arguments are specified after the function name, inside the parentheses.
* You can add as many arguments as you want, just separate them with a comma.
  
example:
def my_function(fname):
  print(fname + " Refsnes")

my_function("Emil")
my_function("Tobias")
my_function("Linus")

parameters or arguments:
* information that are passed into a function.
* A parameter is the variable listed inside the parentheses in the function definition.
* An argument is the value that is sent to the function when it is called.

# Number of Arguments
* By default, a function must be called with the correct number of arguments.
* Meaning that if your function expects 2 arguments, you have to call the function with 2 arguments, not more, and not less.
  
  example
* def my_function(fname, lname):
 * print(fname + " " + lname)

*my_function("Emil", "Refsnes")

# classes and objects

Create a Class
* use the keyword class:
* example
* class MyClass:
 * x = 5

# Create Object
* class MyClass:
  
  8x = 5

* p1 = MyClass()
* print(p1.x)

  





  






  








JUPYTER NOTEBOOK( Interacting with Jupyter Notebook in the browser)

used to write and execute proggraming language
open the app, clieck on new 
In a Jupyter Notebook, new cells can be created by holding down the shift key and pressing enter multiple times.
 To enter Python code, click inside the cell to enter edit mode and start typing.
 To run the code, hold down shift and press enter.

 (Interacting with Jupyter Notebook in VScode)
 making changes on the file you can open the file on Visual Studio Code
 Visual Studio Code( CAN EDIT, RUN AND do all other thing that can be done on the web browser 





 
 
