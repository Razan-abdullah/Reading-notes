# if __name__ == “__main__”:?

Before executing code, Python interpreter reads source file and define few special variables/global variables. 
If the python interpreter is running that module (the source file) as the main program, it sets the special __name__ variable to have a value “__main__”. If this file is being imported from another module, __name__ will be set to the module’s name. Module’s name is available as value to __name__ global variable. 

# A module
 is a file containing Python definitions and statements. The file name is the module name with the suffix .py appended. 

When we execute file as command to the python interpreter,  
```{
python script.py
}
```

# Python program to execute
# function directly
def my_function():
    print ("I am inside function")
 
# We can test function by calling it.
my_function()
Now if we want to use that module by importing we have to comment out our call. Rather than that approach best approach is to use following code: 


## Advantages : 

* Every Python module has it’s __name__ defined and if this is ‘__main__’, it implies that the module is being run standalone by the user and we can do corresponding appropriate actions.
* If you import this script as a module in another script, the __name__ is set to the name of the script/module.
* Python files can act as either reusable modules, or as standalone programs.
* if __name__ == “main”: is used to execute some code only if the file was run directly, and not imported.
* This article is contributed by Nirmi Shah. If you like GeeksforGeeks and would like to contribute, you can also write an article using contribute.geeksforgeeks.org or mail your article to contribute@geeksforgeeks.org. See your article appearing on the GeeksforGeeks main page and help other Geeks.


---

## What on Earth is Recursion?
In functional programming, recursion is the core. However, recursion stands to be one of the more difficult concepts to understand.

I myself had been programming in Swift and Python, but I never truly understood recursion until now. The reason it’s hard to understand it because the idea of recursion is not very common in the real world. So, it seems a bit confusing to the novice programmers (or programmers 👨‍💻).

---

## Modular programming refers to the process of breaking a large, unwieldy programming task into separate, smaller, more manageable subtasks or modules. Individual modules can then be cobbled together like building blocks to create a larger application.

There are several advantages to modularizing code in a large application:

Simplicity: Rather than focusing on the entire problem at hand, a module typically focuses on one relatively small portion of the problem. If you’re working on a single module, you’ll have a smaller problem domain to wrap your head around. This makes development easier and less error-prone.

Maintainability: Modules are typically designed so that they enforce logical boundaries between different problem domains. If modules are written in a way that minimizes interdependency, there is decreased likelihood that modifications to a single module will have an impact on other parts of the program. (You may even be able to make changes to a module without having any knowledge of the application outside that module.) This makes it more viable for a team of many programmers to work collaboratively on a large application.

Reusability: Functionality defined in a single module can be easily reused (through an appropriately defined interface) by other parts of the application. This eliminates the need to duplicate code.

Scoping: Modules typically define a separate namespace, which helps avoid collisions between identifiers in different areas of a program. (One of the tenets in the Zen of Python is Namespaces are one honking great idea—let’s do more of those!)

Functions, modules and packages are all constructs in Python that promote code modularization.


## Python Modules: 
There are actually three different ways to define a module in Python:

* A module can be written in Python itself.
* A module can be written in C and loaded dynamically at run-time, like the re (regular expression) module.
* A built-in module is intrinsically contained in the interpreter, like the itertools module.

---

# Unit tests and TDD?

Unit tests are some pieces of code to exercise the input, the output and the behaviour of your code. You can write them anytime you want.

### Important aspects about the unit test:

There are some details to pay attention. The first one is the test name. The tests can be considered as your alive documentation. We need to be descriptive about it and to say what is expected and what we are testing. In this case we explicitly said: should return female when the name is from a female.

The test file name should follow the same name of module name. For instance, if our module is gender.py, our test name should be test_gender.py. It’s ideal to separate the tests folder from production code (the implementation) and to have something like this:
```{
mymodule/
 — module.py
 — another_folder/
 — — another_module.py
tests/
 — test_module.py
 — another_folder/
 — — test_another_module.py

 }```

