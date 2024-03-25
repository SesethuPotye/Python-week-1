s# FUNCTIONS
* A function is a block of code which only runs when it is called.
* Functions are composed of a name and parameters, which are denoted by the def statement.
* A function can return data as a result.

# Creating a Function
In Python a function is defined using the def keyword:

example:

     def my_function():
        print("Hello from a function")
# CALLING A FUNCTION
To call a function we use the function name fallowed by the parenthesis:

example

    def my_function():
      print("Hello from a function")
    my_function()
    
other example that takes 2 paramaters and an operation

    def performOperation( num, num2, operation):
     if operation == "sum "
         return num1 + num2
     if operation == "multiply"
         return num1 * num2
     performOperation(2,3 "sum"")
     
ARGUMENTS
* Information can be passed into functions as arguments
* Arguments are specified after the function name, inside the parentheses
* Aguments can be separated with a comma if you want to add many of them
* Arguments are often shortened to args in Python documentations.

example of a function with 1 argument

    def my_function(fname)
      print(fname + "Refsenses"
    my_function("Emil")
    my_function("Tobias")
    my_function("Linus")
    
named parameters eg, adding a key word "message" to our function

       def performOperation(num1, num2, operation= "sum",  message="Default message"):
           print(message)
           if operation == "sum":
             return num1 + num2
           if operation == "multiply":
             return num1 * num2

    performOperation(2,3, message= "A new message!", operation="multiply")
    A new message!
    
# rules when using key word arguments
* they must come after the positional arguments
* The order of the first two arguments is important and cannot be changed. However
* You can also send arguments with the key = value syntax.
* after these mandatory arguments, the keyword arguments can be in any order. 

# Arbitrary Arguments, *args
(is used befor the parameter name in a function def when  you dont know how many arguments that will be passed into your function)

    def performOperation(*args):
        print(args)
    perfomOperations(1,2,3)
    (1,2,3)

# Arbitrary Keyword Arguments, **kwargs

* If you do not know how many keyword arguments that will be passed into your function, add two asterisk: ** before the parameter name in the function definition.
* This way the function will receive a dictionary of arguments, and can access the items
* accordingly:
* keyword arguments have keys and values and can be passed in any order.

example

    def my_function(**kid):
      print("His last name is " + kid["lname"])

    my_function(fname = "Tobias", lname = "Refsnes")

#  Variables and Scope

Function Scope
* *args and **kwargs were used to print out the arguments passed into a function. This allowed us to see a tuple and dictionary of the passed arguments.

# "locals" function.

* another method that allows us to access all the variables within a Python function without any asterisks.
* local are defined inside the function.

# Globals()
* can be created out side a function




    


    


    





