<h1 align = "center"> Welcome to My GitHub Page</h1>

Glenn B. Dacones  
May 31, 2022  
Foundation of Programming: Python  
Assignment 07  
[My Github Repository](https://github.com/uwpce-Dgbjccd05/IntroToProg-Python-Mod07)
<br/>
<h3 align = "center">Exception Handling & Pickling</h3>
<br/>

#### Introduction  
This paper is about the exception handling & pickling. I will use the knowledge I gather from the internet and incorporate them into my python script.

#### Exception Handling
##### What is Exception?
An exception is an event,  which  an event, which occurs during the execution of a program that disrupts the normal flow of the program's instructions. In general, when a Python script encounters a situation that it cannot cope with, it raises an exception. An exception is a Python object that represents an error.

When a Python script raises an exception, it must either handle the exception immediately otherwise it terminates and quits.

##### Handling an Exception
If you have some suspicious code that may raise an exception, you can defend your program by placing the suspicious code in a try: block. After the try: block, include an except: statement, followed by a block of code which handles the problem as elegantly as possible. I chose this site because it has a list of standard exceptions. (External Reference: [https://www.tutorialspoint.com/python/python_exceptions.htm](https://www.tutorialspoint.com/python/python_exceptions.htm)). (Figure 1).

<img src="https://github.com/uwpce-Dgbjccd05/IntroToProg-Python-Mod07/blob/main/docs/images/try_except.png">  

***Figure 1. An example of exception handling.***

Below is a sample of exception handling in my script (Figure 2).  

try:  
    Processor.read_data_from_file( file_name=file_name_str, list_of_rows=table_lst)  # read file data
except Exception as e:  
    print("\n",e.__doc__, "\n")  
    print(e.__str__())  
    print()  
    

<img src="https://github.com/uwpce-Dgbjccd05/IntroToProg-Python-Mod07/blob/main/docs/images/exception_handling_output.png">  

***Figure 2. An example of exception handling code (top) and output (bottom).

#### Pickling
Python pickle module is used for serializing and de-serializing python object structures. The process to converts any kind of python objects (list, dict, etc.) into byte streams (0s and 1s) is called pickling or serialization or flattening or marshalling. We can converts the byte stream (generated through pickling) back into python objects by a process called as unpickling. (External Reference: [https://www.tutorialspoint.com/python-pickling](https://www.tutorialspoint.com/python-pickling)). 

