# Destructor in Python

This project demonstrates how to implement a **destructor** in Python using a simple class.

## 🚀 Overview

The program defines a class `Demo` with:

- A **constructor** `__init__` that initializes an instance variable and prints a message.
- A **destructor** `__del__` that prints a message when the object is destroyed.

## 🧠 Algorithm

1. Define a class named `Demo`.
2. Inside the class, define the `__init__` method:
   - Initialize an instance variable `status` with the value `"Alive"`.
   - Print the value of `status`.
3. Define the `__del__` method:
   - Print a message indicating the object is being destroyed.
4. Outside the class:
   - Create an instance of the `Demo` class.
   - Delete the object using the `del` keyword.
## Program
class Demo:
    def __init__(self):
        self.value = 10
        print("Constructor called")

    def __del__(self):
        print("Destructor called")

obj = Demo()
print("Value:", obj.value)
del obj

## 🧪 Output
Constructor called
Value: 10
Destructor called

## Result
Thus, the constructor and destructor were implemented successfully in Python.

