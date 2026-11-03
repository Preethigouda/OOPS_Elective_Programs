# OOPS_Elective_Programs
This repository contains the C++ programs completed as part of the Object-Oriented Programming (OOPS) Elective coursework.

The programs begin with fundamental C++ concepts and gradually cover object-oriented programming topics such as classes, constructors, destructors, static members, friend functions, and inheritance.

---
---

## 👨‍🎓 Student Details

| Field        | Details      |
| ------------ | ------------ |
| **Name**     | G.Preethi    |
| **Roll No.** | 642          |
| **Division** | F            |
| **SRN**      | 01FE23BEC341 |
| **Semester** | VII          |

---

## 📂 Project Organization

The repository is arranged class-wise so that the programs can be easily accessed according to the session in which they were covered.

```text
OOPS_Elective_Programs/
│
├── Programs/
│   ├── Class_1/
│   ├── Class_2/
│   ├── Class_3/
│   ├── Class_4/
│   ├── Class_5/
│   ├── Class_6/
│   ├── Class_7/
│   ├── Class_8/
│   ├── Class_9/
│   ├── Class_10/
│   ├── Class_11/
│   └── Class_12/
│
├── Screenshots of errors/
│
├── .gitignore
└── README.md
```

Each class folder contains the programs covered during that respective class/session.

---
## 📚 Class-wise Programs

### Class 1 – C++ Fundamentals

The first class focuses on fundamental C++ programming, including input/output, variables, strings, and different methods of passing parameters.

| Program | Concept |
|---|---|
| `prog_1.cpp` | Basic output using `cout` |
| `prog_2.cpp` | User input and addition of two numbers |
| `prog_3.cpp` | Basic data types and variable declaration |
| `prog_4.cpp` | Area of a rectangle using user input |
| `prog_5.cpp` | Finding the largest number in a list |
| `prog_6.cpp` | Finding string length using C-style and C++-style approaches |
| `prog_7.cpp` | C-style string palindrome checking |
| `prog_8.cpp` | C++-style palindrome program – incomplete practice program |
| `prog_9.cpp` | Parameter passing – pass by value |
| `prog_10.cpp` | Parameter passing – pass by reference |
| `prog_11.cpp` | Parameter passing – pass by pointer |

---

### Class 2 – Classes and Objects

This class introduces the basic structure of object-oriented programming through classes, objects, data members, and member functions.

| Program | Concept |
|---|---|
| `prog_1.cpp` | Creating a class and object; accessing private data through member functions |
| `prog_2.cpp` | Student class with data members and member functions |
| `prog_3.cpp` | Defining a class member function outside the class |
| `prog_4.cpp` | Rectangle class with member functions for setting values and calculating area |
| `prog_5.cpp` | Improved Rectangle program with a function returning the calculated area |

---

### Class 3 – Member Functions and Constructors

The programs in this class focus on working with objects and understanding different types of constructors.

| Program | Concept |
|---|---|
| `prog_1.cpp` | `Time` class and addition of two time objects |
| `prog_2.cpp` | Addition of two complex numbers using objects |
| `prog_3.cpp` | Default constructor for initializing employee data |
| `prog_4.cpp` | Default and parameterized constructors |
| `prog_5.cpp` | Parameterized constructor using a `Distance` class |
| `prog_6.cpp` | Default, parameterized, and copy constructors |

---

### Class 4 – Destructors and Static Data Members

This class deals with the destruction of objects and the use of static members that are common to objects belonging to the same class.

| Program | Concept |
|---|---|
| `prog_1.cpp` | Destructor with a class having default, parameterized, and copy constructors |
| `prog_2.cpp` | Static data member shared by multiple objects |
| `prog_3.cpp` | Static counter with a separate employee ID for each object |

> **Note:** The second and third programs demonstrate how a static data member is shared across objects and how it can be used for maintaining common information.

---

### Class 5 – Static Member Functions and Friend Functions

This class extends the use of static members and introduces friend functions for accessing private class information.

| Program | Concept |
|---|---|
| `prog_1.cpp` | Static member function and static data member |
| `prog_2.cpp` | Friend function accessing private members of a class |
| `prog_3.cpp` | Practice program for friend function parameters |
| `prog_4.cpp` | Common friend function accessing private data from two classes |

---

### Class 6 – Inheritance

The sixth class introduces inheritance and demonstrates how properties and functions can be passed from one class to another.

| Program | Concept |
|---|---|
| `prog_1.cpp` | Single-level inheritance using `Animal` and `Dog` |
| `prog_2.cpp` | Multi-level inheritance using `Person`, `Student`, and `IT_Student` |
| `prog_3.cpp` | Multi-level inheritance and experimentation with access modes |

---

### Class 7 – Multi-level Inheritance and Access Control

The final class continues the study of multi-level inheritance and focuses on the use of protected members.

| Program | Concept |
|---|---|
| `prog_1.cpp` | Multi-level inheritance using `Vehicle`, `Car`, and `Sports Car` |
| `prog_2.cpp` | Multi-level inheritance using `protected` members |

---

### Class 8 – Constructor Initializer Lists and Multiple Inheritance

The programs in this class focus on constructor initializer lists, base-class and derived-class initialization, multiple inheritance, and student result calculations.

| Program | Concept |
|---|---|
| `prog_1.cpp` | Single-level inheritance using constructor initializer lists |
| `prog_2.cpp` | Multi-level inheritance using Person, Student, and IT_Student |
| `prog_3.cpp` | Multiple inheritance using Student, Test, and Result |
| `prog_4.cpp` | Parameterized constructors and initializer lists using Student, Test, and Result |
| `prog_5.cpp` | Student result calculation using multiple inheritance with three subject marks |
| `prog_6.cpp` | Student result calculation using multiple inheritance with five subject marks |

---

### Class 9 – Multiple Inheritance

The programs in this class focus on multiple inheritance, where a derived class inherits properties and member functions from more than one base class.

| Program | Concept |
|---|---|
| `prog_1.cpp` | Multiple inheritance using Liquid, Fuel, and derived class Petrol |
| `prog_2.cpp` | Student, Test, and Result multiple-inheritance example; an intermediate constructor/display practice version |

> **Note:** The Class 9 folder contains `prog_1.cpp` and `prog_2.cpp`. Class 8 also includes related versions of the student-result example.

---

### Class 10 – Virtual Base Classes and Function Overriding

The programs in this class focus on virtual base classes, resolving ambiguity in multiple inheritance, function overriding, and runtime polymorphism using virtual functions.

| Program | Concept |
|---|---|
| `prog_1.cpp` | Diamond-style multiple inheritance where member `i` becomes ambiguous because D inherits A through both B and C |
| `prog_2.cpp` | Resolving repeated-base ambiguity using a virtual base class |
| `prog_3.cpp` | Function overriding with a virtual `show()` function and base-class pointer; demonstrates runtime polymorphism (late binding) |
| `prog_4.cpp` | Further practice with base and derived `show()` functions, virtual dispatch, and direct object calls |

---

### Class 11 – Runtime Polymorphism, Abstract Classes, and Operator Overloading

The programs in this class focus on virtual functions, runtime polymorphism, abstract classes, and unary and binary operator overloading in C++.

| Program | Concept |
|---|---|
| `prog_1.cpp` | Shape base class and Circle derived class; virtual `draw()` demonstrates runtime polymorphism |
| `prog_2.cpp` | One base class with three derived classes (Circle, Square, and Triangle) overriding `draw()` |
| `prog_3.cpp` | Runtime polymorphism using an array of base-class pointers to different derived shape objects |
| `prog_4.cpp` | Abstract Vehicle class with a pure virtual function and derived Car and Bike classes |
| `prog_5.cpp` | Binary `+` operator overloading to add two complex numbers |
| `prog_6.cpp` | Binary `-` operator overloading to subtract two complex numbers |
| `prog_7.cpp` | Prefix and postfix increment operator overloading (`++`) for a Counter class |
| `prog_8.cpp` | Prefix/postfix-style decrement logic practice; review the operator names in the current source, which still use `operator++` |

---

### Class 12 – String Operator Overloading and Exception Handling

The programs in this class focus on operator overloading for string concatenation and exception handling using `try`, `throw`, and `catch` blocks.

| Program | Concept |
|---|---|
| `prog_1.cpp` | Practice with binary `+` operator overloading for string concatenation; current source contains issues to correct |
| `prog_2.cpp` | Basic exception handling using `try`, `throw`, and `catch` for a negative integer |
| `prog_3.cpp` | Throwing and catching an integer when one of two values is zero |
| `prog_4.cpp` | Exception handling with different thrown data types (`int` and `double`) and matching catch blocks |
| `prog_5.cpp` | Handling division by zero by throwing and catching a message |
| `prog_6.cpp` | Modified division-by-zero example exploring the order of division and exception throwing |

---

## 🧠 Concepts Covered

The repository includes the following C++ and OOPS concepts:

### Basic C++ Concepts
- Basic C++ syntax, variables, and data types
- Input and output using `cin` and `cout`

### Functions and Parameter Passing
- Pass by value
- Pass by reference
- Pass by pointer

### Strings
- C-style strings
- C++-style strings

### Classes and Objects
- Classes, objects, data members, and member functions
- Member functions defined outside a class

### Constructors
- Default constructor
- Parameterized constructor
- Copy constructor
- Constructor initializer lists

### Destructors
- Destructors and object destruction

### Static Members
- Static data members
- Static member functions

### Friend Functions
- Friend functions accessing private class members
- Friend functions accessing members of multiple classes

### Inheritance
- Single-level inheritance
- Multi-level inheritance
- Multiple inheritance
- Virtual base classes and the diamond problem
- Access specifiers
  - `private`
  - `public`
  - `protected`
- Function overriding
- Virtual functions, late binding, and runtime polymorphism
- Abstract classes and pure virtual functions

### Operator Overloading
- Binary `+` and `-` operators
- Prefix and postfix increment/decrement operators

### Exception Handling
- `try`
- `throw`
- `catch`
- Handling different exception types
- Division-by-zero examples

---

## 💻 Programming Language

**C++**

The programs use standard C++ features and headers such as:

```cpp
#include <iostream>
#include <cstring>
```

---

## 🛠️ Tools Used

- **C++**
- **GCC / G++ compiler**
- **Visual Studio Code**
- **Git**
- **GitHub**

---

## ▶️ How to Run

### Option 1: Run using Code::Blocks

The programs can be compiled and executed using **Code::Blocks** with a C++ compiler.

1. Open **Code::Blocks**.
2. Go to **File → Open** and select the required `.cpp` file.
3. If Code::Blocks asks for a compiler, select/configure the installed **GCC / MinGW** compiler.
4. Open the program you want to execute.
5. Click **Build and Run** or press:

```text
F9
```

6. The program output will appear in the **Console** window.

For example, to run:

```text
Programs/
└── Class_1/
    └── prog_1.cpp
```

Open `prog_1.cpp` in Code::Blocks and use **Build → Build and Run**.

> **Note:** Most of these programs are standalone `.cpp` files, so they can be opened and run individually without creating a large project containing all programs.

### Option 2: Run using Visual Studio Code

Open the repository folder in Visual Studio Code.

Compile a program using G++:

```bash
g++ Programs/Class_1/prog_1.cpp -o program
```

Run the compiled program on Windows:

```bash
program.exe
```

Or, depending on the terminal:

```bash
./program
```

You can replace the file path with any `.cpp` program you want to execute.

### Option 3: Clone the repository first

```bash
git clone https://github.com/Preethigouda/OOPS_Elective_Programs.git
```

Then open the cloned folder in **Code::Blocks, Visual Studio Code, or another C++ IDE**.

---

## 📸 Screenshots / Errors

The `Screenshots of errors` folder contains screenshots related to errors encountered while developing and testing the programs.

These are included as part of the learning and debugging process.

---

## 📌 Notes

Some programs are intentionally kept in their original coursework/practice form. A few files contain incomplete experiments or code written while exploring a particular concept.

The repository is primarily intended for **coursework, learning, practice, and revision of C++ OOPS concepts**.

---

## 👨‍💻 Author

**G Preethi**

Electronics and Communication Engineering (ECE)

---

⭐ If you find this repository helpful for understanding C++ and OOPS concepts, you can consider giving it a star.
