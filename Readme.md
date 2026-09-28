# 🏢 Python OOP Wrapper Project

---

**Author:** Drashti Vasani

---

## 📌 Project Description

The **OOP_wrapper** is a menu-driven Python project developed using **Object-Oriented Programming (OOP)** concepts.

This project demonstrates important OOP concepts such as **Classes, Objects, Inheritance, Encapsulation, Method Overriding, Constructors, Getters, Setters, `super()`, `issubclass()` and Destructor**.

The system allows users to create and display details of different types of people and employees, including **Person, Employee, Manager, and Developer**.

---

## 🎯 Objectives

The main objectives of this project are:

* To understand the fundamentals of Python OOP.
* To create and use classes and objects.
* To implement inheritance.
* To demonstrate encapsulation.
* To implement method overriding.
* To use constructors and destructors.
* To understand the use of `super()`.
* To use getter and setter methods.
* To check inheritance using `issubclass()`.
* To create a menu-driven Python application.

---

## ✨ Features

* 👤 Create a Person
* 👨‍💼 Create an Employee
* 👔 Create a Manager
* 👨‍💻 Create a Developer
* 📋 Display details of created objects
* 🔐 Encapsulation of Employee ID and Salary
* 🔄 Method overriding
* 🧬 Inheritance between classes
* ✅ Subclass checking using `issubclass()`
* 🚪 Exit the system

---

## 🧩 Classes Used

### 1. Person

`Person` is the parent/base class.

**Attributes:**

* Name
* Age

**Method:**

* `display()`

### 2. Employee

`Employee` inherits from the `Person` class.

**Attributes:**

* Employee ID
* Salary

**Methods:**

* `get_salary()`
* `set_salary()`
* `get_emp_id()`
* `display()`

### 3. Manager

`Manager` inherits from the `Employee` class.

**Additional Attribute:**

* Department

### 4. Developer

`Developer` inherits from the `Employee` class.

**Additional Attribute:**

* Programming Language

---

## 🧠 OOP Concepts Demonstrated

### 🔹 Class and Object

Classes are used as blueprints, and objects are created from those classes.

```python
person = Person(name, age)
employee = Employee(name, age, emp_id, salary)
```

### 🔹 Inheritance

```text
Person
   ↓
Employee
   ↓
Manager
```

```text
Person
   ↓
Employee
   ↓
Developer
```

### 🔹 Encapsulation

Employee ID and Salary are stored as private attributes.

```python
self.__emp_id
self.__salary
```

### 🔹 Method Overriding

The `display()` method is overridden in the `Employee`, `Manager`, and `Developer` classes.

### 🔹 Constructor

The `__init__()` method initializes object data.

### 🔹 `super()`

`super()` is used to access parent class functionality.

### 🔹 `issubclass()`

The program checks whether `Manager` and `Developer` are subclasses of `Employee`.

```python
issubclass(Manager, Employee)
issubclass(Developer, Employee)
```

**Output:**

```text
Manager is subclass of Employee: True
Developer is subclass of Employee: True
```

### 🔹 Destructor

The Employee class contains a destructor method:

```python
def __del__(self):
    pass
```

---

## 📋 Main Menu

```text
Choose an operation:
1. Create a Person
2. Create an Employee
3. Create a Manager
4. Create a Developer
5. Show Details
6. Exit
```

---

## 📊 Show Details Menu

```text
Choose details to show:
1. Person
2. Employee
3. Manager
4. Developer
```

## 🛠️ Technologies Used

* Python 3
* Object-Oriented Programming (OOP)
* Classes and Objects
* Inheritance
* Encapsulation
* Method Overriding
* Constructors
* Destructor
* Getter and Setter Methods

---

## ▶️ How to Run

### Step 1: Check Python

```bash
python --version
```

### Step 2: Clone the Repository

```bash
git clone YOUR_REPOSITORY_LINK
```

### Step 3: Open the Project Folder

```bash
cd OOP_wrapper
```

### Step 4: Run the Program

```bash
python OOP_wrapper.py
```

---

## 📁 Project Structure


```text
OOP_wrapper/
│
├── OOP_wrapper.py
├── output.png
└── README.md
```

---

## 📚 What I Learned

Through this project, I learned:

* Creating classes and objects.
* Using constructors.
* Implementing inheritance.
* Implementing encapsulation.
* Using private attributes.
* Creating getter and setter methods.
* Implementing method overriding.
* Using `super()`.
* Checking inheritance using `issubclass()`.
* Creating a menu-driven Python application.

---

## 🚀 Future Improvements

* Add employee update functionality.
* Add employee delete functionality.
* Store multiple employee records.
* Add employee search functionality.
* Add file handling.
* Add database connectivity.
* Add GUI functionality.

---

## 📌 Conclusion

The **OOP_Wrapper** is a beginner-friendly Python project that demonstrates the practical use of important **Object-Oriented Programming concepts**.

This project helps in understanding how different OOP concepts can be combined to create a structured and interactive Python application.

---

## 💻 Sample Output

The following is the actual sample output from the project:

```text
--- Python OOP Project: Employee Management System ---

--- Subclass Checking ---
Manager is subclass of Employee: True
Developer is subclass of Employee: True

Choose an operation:
1. Create a Person
2. Create an Employee
3. Create a Manager
4. Create a Developer
5. Show Details
6. Exit

Enter your choice: 1
Enter Name: drashti
Enter Age: 20

Person created with name: drashti and age: 20

--- Choose another operation ---

Choose an operation:
1. Create a Person
2. Create an Employee
3. Create a Manager
4. Create a Developer
5. Show Details
6. Exit

Enter your choice: 2
Enter Name: viraj
Enter Age: 23
Enter Employee ID: 12661
Enter Salary: 20000

Employee created with name: viraj age: 23 ID: 12661 and salary: $ 20000.0

--- Choose another operation ---

Choose an operation:
1. Create a Person
2. Create an Employee
3. Create a Manager
4. Create a Developer
5. Show Details
6. Exit

Enter your choice: 3
Enter Name: janvi
Enter Age: 24
Enter Employee ID: 12662
Enter Salary: 30000
Enter Department: hr

Manager created with name: janvi age: 24 ID: 12662 salary: $ 30000.0 and department: hr

--- Choose another operation ---

Choose an operation:
1. Create a Person
2. Create an Employee
3. Create a Manager
4. Create a Developer
5. Show Details
6. Exit

Enter your choice: 4
Enter Name: kaushik
Enter Age: 24
Enter Employee ID: 12665
Enter Salary: 40000
Enter Programming Language: python

Developer created with name: kaushik age: 24 ID: 12665 salary: $ 40000.0 and programming language: python

--- Choose another operation ---

Choose an operation:
1. Create a Person
2. Create an Employee
3. Create a Manager
4. Create a Developer
5. Show Details
6. Exit

Enter your choice: 5

Choose details to show:
1. Person
2. Employee
3. Manager
4. Developer
Enter your choice: 3

Manager Details:
Name: janvi
Age: 24
Employee ID: 12662
Salary: $ 30000.0
Department: hr

--- Choose another operation ---

Choose an operation:
1. Create a Person
2. Create an Employee
3. Create a Manager
4. Create a Developer
5. Show Details
6. Exit

Enter your choice: 6

Exiting the system. All resources have been freed.
Goodbye!
```

---

                                             **⭐ Thank you for visiting this project! ⭐**

---

