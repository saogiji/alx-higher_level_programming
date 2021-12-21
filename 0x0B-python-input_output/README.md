# 0x0B. Python - Input/Output
## Introduction
A predefined function input() is available in python to take input from the keyboard during runtime. This function takes a value from the keyboard and returns it as a string type. Based on the requirement we can convert from string to other types.
Example: 
````
name = input("Enter the name: ")
print("You entered name as: ", name)
````
## Tasks/Projects
### 0. Read file
A function that reads a text file (UTF8) and prints it to stdout:
* Prototype: def read_file(filename=""):
* You must use the with statement
* You don’t need to manage file permission or file doesn't exist exceptions.
* You are not allowed to import any module.
### 1. Write to a file
A function that writes a string to a text file (UTF8) and returns the number of characters written:
* Prototype: `def write_file(filename="", text=""):`
* You must use the with statement
* You don’t need to manage file permission exceptions.
* Your function should create the file if doesn’t exist.
* Your function should overwrite the content of the file if it already exists.
* You are not allowed to import any module