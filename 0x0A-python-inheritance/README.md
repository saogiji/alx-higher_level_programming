# 0x0A. Python - Inheritance
## Introduction
Inheritance is one of the core concepts of object-oriented programming (OOP) languages. It is a mechanism where you can to derive a class from another class for a hierarchy of classes that share a set of attributes and methods.
It can be used to declare different kinds of exceptions, add custom logic to existing frameworks, and even map your domain model to a database.
Python has two built-in functions that work with inheritance:
1. Use `isinstance()` to check an instance’s type: `isinstance(obj, int)` will be `True` only if `obj.__class__` is `int` or some class derived from `int`.
2. Use `issubclass()` to check class inheritance: `issubclass(bool, int)` is `True` since `bool` is a subclass of `int`. However, `issubclass(float, int)` is `False` since `float` is not a subclass of `int`.
## Tasks/Projects
### 0. Lookup
A function that returns the list of available attributes and methods of an object:
### 1. My list
A  class MyList that inherits from list:
5B