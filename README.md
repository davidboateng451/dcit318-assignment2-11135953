# dcit318-assignment2-11135953
# DCIT318 - Assignment 2

Student ID: 11135953  
Course: DCIT 318  
Description: This repository contains three C# console applications developed as part of Assignment 2. Each application demonstrates a key concept in *Object-Oriented Programming (OOP): inheritance, abstraction, and interfaces.


## 📁 Projects Included

### 1. 🐾 OOP Inheritance and Method Overriding
- Description: Demonstrates inheritance and method overriding using an `Animal` base class and two derived classes:
  - `Dog`: Overrides `MakeSound()` to print `"Bark"`
  - `Cat`: Overrides `MakeSound()` to print `"Meow"`
- Base Method: `Animal.MakeSound()` → prints `"Some generic sound"`
- Folder: `OOPInheritance`


### 2. 📐 Abstract Classes and Methods
- Description: Uses an abstract base class `Shape` with an abstract method `GetArea()`:
  - `Circle`: Implements `GetArea()` using πr²
  - `Rectangle`: Implements `GetArea()` using width × height
- Demonstrates: Abstract classes and polymorphism
- Folder: `OOPAbstraction`


### 3. 🚗 Interfaces and Implementation
- Description: Defines an `IMovable` interface with a `Move()` method:
  - `Car`: Implements `Move()` to print `"Car is moving"`
  - `Bicycle`: Implements `Move()` to print `"Bicycle is moving"`
- Demonstrates: Interfaces and implementation in different classes
- Folder: `OOPInterfaces`


## 💻 How to Run
To run any of the applications:

1. Open the solution or individual project in **Visual Studio**
2. Set the desired project as the **Startup Project**
3. Press `Ctrl + F5` or click **"Start Without Debugging"**


## 📌 Notes
- All applications are written in **C#** using the **.NET Console Application** template.
- Each project is committed separately to demonstrate individual OOP concepts.


