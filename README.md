<h1 align = "center"> Welcome to My GitHub Page</h1>

Glenn B. Dacones  
May 24, 2022  
Foundation of Programming: Python  
Assignment 07  
[My Github Repository](https://github.com/uwpce-Dgbjccd05/IntroToProg-Python-Mod07)

<br/>
<h3 align = "center">Exception Handling & Pickling</h3>
<br/>

#### Introduction
This paper is about the exception handling & pickling. I will use the knowledge I gather from the internet and incorporate them into my python script.

#### What is Exception Handling?
##### What is Exception?
An exception is an event,  which  an event, which occurs during the execution of a program that disrupts the normal flow of the program's instructions. In general, when a Python script encounters a situation that it cannot cope with, it raises an exception. An exception is a Python object that represents an error.

When a Python script raises an exception, it must either handle the exception immediately otherwise it terminates and quits.

##### Handling an Exception
If you have some suspicious code that may raise an exception, you can defend your program by placing the suspicious code in a try: block. After the try: block, include an except: statement, followed by a block of code which handles the problem as elegantly as possible. I chose this site because it has a list of standard exceptions as shown below. (External Reference: https://www.tutorialspoint.com/python/python_exceptions.htm).

Exception Name & Description
Exception: Base class for all exceptions
StopIteration: Raised when the next() method of an iterator does not point to any object.
SystemExit: Raised by the sys.exit() function.
StandardError: Base class for all built-in exceptions except StopIteration and SystemExit.
ArithmeticError: Base class for all errors that occur for numeric calculation.
OverflowError: Raised when a calculation exceeds maximum limit for a numeric type.
FloatingPointError: Raised when a floating point calculation fails.
ZeroDivisionError: Raised when division or modulo by zero takes place for all numeric types.
AssertionError: Raised in case of failure of the Assert statement.
AttributeError: Raised in case of failure of attribute reference or assignment.
EOFError: Raised when there is no input from either the raw_input() or input() function and the end of file is reached.
ImportError: Raised when an import statement fails.
KeyboardInterrupt: Raised when the user interrupts program execution, usually by pressing Ctrl+c.
LookupError: Base class for all lookup errors.
IndexError: Raised when an index is not found in a sequence.
KeyError: Raised when the specified key is not found in the dictionary.
NameError: Raised when an identifier is not found in the local or global namespace.
UnboundLocalError: Raised when trying to access a local variable in a function or method but no value has been assigned to it.
EnvironmentError: Base class for all exceptions that occur outside the Python environment.
IOError: Raised when an input/ output operation fails, such as the print statement or the open() function when trying to open a file that does not exist.
IOError: Raised for operating system-related errors.
SyntaxError: Raised when there is an error in Python syntax.
IndentationError: Raised when indentation is not specified properly.
SystemError: Raised when the interpreter finds an internal problem, but when this error is encountered the Python interpreter does not exit.
SystemExit: Raised when Python interpreter is quit by using the sys.exit() function. If not handled in the code, causes the interpreter to exit.
TypeError: Raised when an operation or function is attempted that is invalid for the specified data type.
ValueError: Raised when the built-in function for a data type has the valid type of arguments, but the arguments have invalid values specified.
RuntimeError: Raised when a generated error does not fall into any category.
NotImplementedError: Raised when an abstract method that needs to be implemented in an inherited class is not actually implemented.


#### Pickling
 

