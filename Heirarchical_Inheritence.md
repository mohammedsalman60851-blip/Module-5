# Hierarchical Inheritance in Python

This Python project demonstrates **Hierarchical Inheritance** using a base class `Details` and two derived classes `Employee` and `Patient`. The program collects and displays details for both employees and patients.

## 🎯 Aim

To write a Python program that uses **Hierarchical Inheritance** to input and display **Employee** and **Patient** details.

## 📘 Description

- **Base Class:** `Details`
  - Stores common attributes: `name`, `age`
  - Provides methods: `getName()`, `getAge()`

- **Derived Class 1:** `Employee`
  - Inherits from `Details`
  - Adds: `employee_id`, `department`
  - Method: `getEmployeeDetails()`

- **Derived Class 2:** `Patient`
  - Inherits from `Details`
  - Adds: `patient_id`, `disease`
  - Method: `getPatientDetails()`

## 🧠 Algorithm

1. Create base class `Details` with common attributes.
2. Create `Employee` class extending `Details`, adding employee-specific data.
3. Create `Patient` class extending `Details`, adding patient-specific data.
4. Get user input for employee and patient data.
5. Display collected information using class methods.

## Program
class Person:
    def __init__(self):
        self.name = input("Enter name: ")
        self.age = int(input("Enter age: "))

class Employee(Person):
    def display(self):
        print("Employee Details")
        print("Name:", self.name)
        print("Age:", self.age)

class Patient(Person):
    def display(self):
        print("Patient Details")
        print("Name:", self.name)
        print("Age:", self.age)

print("Enter Employee Details")
emp = Employee()
emp.display()

print("\nEnter Patient Details")
pat = Patient()
pat.display()
## Sample Output
Enter Employee Details
Enter name: Salman
Enter age: 20
Employee Details
Name: Salman
Age: 20

Enter Patient Details
Enter name: Rahul
Enter age: 25
Patient Details
Name: Rahul
Age: 25

## result
Thus, the Python program using hierarchical inheritance to input and display Employee and Patient details was executed successfully.


