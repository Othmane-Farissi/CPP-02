# CPP-02

## Overview

This repository is part of the 42 School C++ modules, specifically covering **Module 02**. The focus is on understanding C++ basics such as references, pointers, memory management, and the "Orthodox Canonical Form" (O.C.F) of classes. The exercises are designed to deepen your knowledge of object-oriented programming, class design, and resource management in C++.

## Contents

The project typically includes the following exercises:

1. **ex00 - Fixed-Point Numbers:**  
   - Implements a `Fixed` class to practice operator overloading, constructors, and working with fixed-point arithmetic.

2. **ex01 - OCF & Copy Control:**  
   - Further develops the `Fixed` class, focusing on the Orthodox Canonical Form: default constructor, copy constructor, assignment operator, and destructor.

3. **ex02 - Mini Game (e.g., Point in Triangle):**  
   - Builds upon previous exercises to solve geometric problems, such as determining if a point lies within a triangle using C++ classes.

## Key Concepts Covered

- References and pointers in C++
- Class constructors and destructors
- Copy control: copy constructor and assignment operator
- Operator overloading
- Resource management and RAII
- Encapsulation and abstraction

## How to Use

1. **Clone the repository**
   ```bash
   git clone https://github.com/Othmane-Farissi/CPP-02.git
   cd CPP-02
   ```

2. **Compile the exercises**
   Each exercise folder (e.g., `ex00`, `ex01`, `ex02`) contains its own `Makefile`:
   ```bash
   cd ex00 && make
   ```

3. **Run the executables**
   ```bash
   ./fixed_point
   ```

## Folder Structure

```
CPP-02/
├── ex00/
│   ├── Fixed.cpp
│   ├── Fixed.hpp
│   ├── main.cpp
│   └── Makefile
├── ex01/
│   ├── Fixed.cpp
│   ├── Fixed.hpp
│   ├── main.cpp
│   └── Makefile
├── ex02/
│   ├── Point.cpp
│   ├── Point.hpp
│   ├── bsp.cpp
│   ├── main.cpp
│   └── Makefile
└── README.md
```

## Requirements

- C++ compiler (clang++ or g++)
- Make

## Author

- [Othmane Farissi](https://github.com/Othmane-Farissi)

---

> *For more information about the 42 C++ modules, visit [42 Network](https://github.com/42Network).*
