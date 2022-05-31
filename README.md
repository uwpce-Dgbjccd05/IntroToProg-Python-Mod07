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

![Exception Handling](https://github.com/uwpce-Dgbjccd05/IntroToProg-Python-Mod07/blob/main/docs/images/try_except.png?raw=true "Exception Handling")

***Figure 1. An example of exception handling.***

Below is a sample of exception handling in my script (Figure 2).
<br/>
<br/>
![Exception Handling](https://github.com/uwpce-Dgbjccd05/IntroToProg-Python-Mod07/blob/main/docs/images/try_except_code.png?raw=true "Exception Handling")
![Exception Handling](https://github.com/uwpce-Dgbjccd05/IntroToProg-Python-Mod07/blob/main/docs/images/exception_handling_output.png?raw=true "Exception Handling")

***Figure 2. An example of exception handling code (top) and output (bottom).***

#### Pickling
Python pickle module is used for serializing and de-serializing python object structures. The process to converts any kind of python objects (list, dict, etc.) into byte streams (0s and 1s) is called pickling or serialization or flattening or marshalling. We can converts the byte stream (generated through pickling) back into python objects by a process called as unpickling. (External Reference: [https://www.tutorialspoint.com/python-pickling](https://www.tutorialspoint.com/python-pickling)). Below shows an example of pickling (Figure 3).

![Pickling](https://github.com/uwpce-Dgbjccd05/IntroToProg-Python-Mod07/blob/main/docs/images/pickling.png?raw=true "Pickling")  
***Figure 3. An example of pickling.***  

Below shows an example of unpickling (Figure 4.)  

![Unpickling](https://github.com/uwpce-Dgbjccd05/IntroToProg-Python-Mod07/blob/main/docs/images/unpickling.png?raw=true "Unickling")  
***Figure 4. An example of unpickling.***  

#### Script Execution
Below shows the script running in PyCharm (Figure 5). 

![PyCharm](https://github.com/uwpce-Dgbjccd05/IntroToProg-Python-Mod07/blob/main/docs/images/PyCharm_Script.png?raw=true "PyCharm")  
***Figure 5. A screenshot of script running in PyCharm.  

Below shows the script running in command shell (Figure 6).  

![Command](https://github.com/uwpce-Dgbjccd05/IntroToProg-Python-Mod07/blob/main/docs/images/CommandShell_Script.png?raw=true "Command")  
***Figure 6. A screenshot of script running in command shell.  

#### Summary
In this assignment, I found several internet sources for exception handling and pickling. Most of the websites provided examples and usage. I chose the website tutorialspoint.com because it also provided a list of standard exceptions.
