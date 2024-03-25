# FUNCTIONS
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
    A new message







