---
title: Object-oriented programming in C++
summary: 
date: 2025-05-30

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com)'
  
authors:
  - admin
tags:
  - Academic
---

{{< toc mobile_only=true is_open=true >}}

Object-oriented programming (OOP) in C++ opens the way to creating flexible, extensible, and well-structured applications. Here are the key ideas.

1. **Classes and objects**
 - A class is a "blueprint" for objects: it describes their properties (fields) and behavior (methods). An object is a specific instance of a class with its own field values.

```cpp
   class Car {
   private:
       std::string model;
       int year;
   public:
       Car(std::string m, int y): model(m), year(y) {}
       void drive() { std::cout << model << " driving..\n"; }
   };
```

2. **Encapsulation**
 - Hiding the internal state of an object (the `private` field) and providing managed access through methods (`public`). This protects the data from misuse and simplifies maintenance.

3. **Inheritance**
- Allows you to create a new class based on an existing one by "inheriting" its properties and methods.

```cpp
   class ElectricCar : public Car {
   private:
       int batteryLevel;
   public:
       ElectricCar(std::string m, int y, int b)
           : Car(m, y), batteryLevel(b) {}
       void charge() { batteryLevel = 100; }
   };
```

4. **Polymorphism**
- The ability to work with different types of objects through a single interface. In C++, this is achieved through virtual methods and pointers/references to the base class.

```cpp
   Car* ptr = new ElectricCar("Tesla", 2021, 80);
   ptr->drive();  // method Car::drive, may be virtual for dynamic binding 
```

5. **Abstraction**
- Creating generalized interfaces (abstract classes) that separate "what it does" from "how it does it." The client of the code interacts only with the methods, hiding the implementation details.

## Why is this important?
OOP helps to develop complex systems by keeping the code readable and scalable. With C++, you gain control over performance and memory along with a powerful set of OOP tools, including constructors, destructors, operator overloading, and templates.
Try designing a simple project in C++, such as a game or accounting system, and see how OOP makes it easier to add new features without rewriting existing code.

---










