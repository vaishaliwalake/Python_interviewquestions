** Q.1. What is Python?** ** 

Python is a high-level, interpreted, interactive, and object-oriented scripting language. Python is designed to be highly readable. It uses English keywords frequently, whereas the other languages use punctuation, and it has fewer syntactical constructions than the other language.

Q.2. What are the key features of Python?

Python is an interpreted language, so it doesn’t need to be compiled before execution, unlike languages such as C.
Python is dynamically typed, so there is no need to declare a variable with the data type. Python Interpreter will identify the data type on the basis of the value of the variable.
Python follows an object-oriented programming paradigm with the exception of having access specifiers. Other than access specifiers (public and private keywords), Python has classes, inheritance, and all other usual OOPs concepts.
Python is a cross-platform language, i.e., a Python program written on a Windows system will also run on a Linux system with little or no modifications at all.
Python is literally a general-purpose language, i.e., Python finds its way in various domains such as web application development, automation, Data Science, Machine Learning, and more.

Q3.What is the purpose of PYTHONPATH environment variable?

PYTHONPATH has a role similar to PATH. This variable tells Python Interpreter where to locate the module files imported into a program. It should include Python source library directory and the directories containing Python source code. PYTHONPATH is sometimes preset by Python Installer.

Q.4 Which data types are supported in Python?

Python has five standard data types:
1.Numbers
2.Strings
3.Lists
4.Tuples
5.Dictionaries

Q.5 What is the difference between lists and tuples?

Lists are mutable, i.e., they can be edited.	Tuples are immutable (they are lists that cannot be edited).
 
 Lists are usually slower than tuples.	Tuples are faster than lists.
 
 Syntax: list_1 = [10, ‘Hello’, 20]	Syntax:tup_1 = (10, ‘Hello’ , 20)
	


Q.6.What is a dictionary in Python?

Python dictionary is one of the supported data types in Python. It is an unordered collection of elements. The elements in dictionaries are stored as key–value pairs. Dictionaries are indexed by keys.
For example, below we have a dictionary named ‘dict’. It contains two keys, Country and Capital, along with their corresponding values, India and New Delhi.
dict={‘Country’:’India’,’Capital’:’New Delhi’, }

Q.7 How are Python arrays and Python lists different from each other?

In Python, when we say ‘arrays’, we are usually referring to ‘lists’. It is because lists are fundamental to Python just as arrays are fundamental to most of the low-level languages.
However, there is indeed a module named ‘array’ in Python, which is used or mentioned very rarely. 
Following are some of the differences between Python arrays and Python lists.
Arrays can only store homogeneous data (data of the same type).	Lists can store heterogeneous and arbitrary data.
Since only one type of data can be stored, arrays use memory for only one type of objects. Thus, mostly, arrays use lesser memory than lists.	Lists can store data of multiple data types and thus require more memory than arrays.
The length of an array is pre-fixed while creating it, so more elements cannot be added.Since the length of a list is not fixed, appending items to it is possible.
