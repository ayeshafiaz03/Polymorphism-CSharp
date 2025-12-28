# Polymorphism – C#

This repository demonstrates the concept of **Polymorphism** in C#, which is one of the core principles of Object-Oriented Programming (OOP).

---

## What is Polymorphism?

Polymorphism means **"many forms"**. In object-oriented programming, it refers to the ability of a single method, function, or object to behave differently based on the context in which it is used.

Polymorphism allows the same method name to perform different tasks, depending on:
- The object that is calling the method
- The type of data or parameters passed
- The class hierarchy involved

This concept improves code **flexibility**, **reusability**, and **maintainability**.

---

## Key Concepts of Polymorphism

- A single method can behave differently for different objects.
- Achieved mainly through:
  - **Method Overriding (Runtime Polymorphism)**
  - **Method Overloading (Compile-Time Polymorphism)**
- Base class reference can point to derived class objects.

---

## Types of Polymorphism in C#

### 1. Compile-Time Polymorphism
- Also known as **method overloading**
- Achieved by having multiple methods with the same name but different parameters
- Method selection happens at compile time

### 2. Run-Time Polymorphism
- Achieved through **method overriding**
- Uses inheritance and virtual methods
- Method selection happens at runtime based on object type

---

## Why Polymorphism is Important?

- Makes code more scalable
- Supports loose coupling
- Enhances readability
- Simplifies maintenance
- Plays a key role in real-world object modeling
