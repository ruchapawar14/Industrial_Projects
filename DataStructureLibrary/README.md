# Generic Data Structure Library (C++)

![C++](https://img.shields.io/badge/C++-Generic%20Programming-blue?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Data Structures](https://img.shields.io/badge/Data%20Structures-Linked%20List%20%7C%20Stack%20%7C%20Queue-orange?style=for-the-badge)
![OOP](https://img.shields.io/badge/Paradigm-Object%20Oriented-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Educational-informational?style=for-the-badge)

A template-based implementation of fundamental linear data structures in C++, built from scratch without using STL containers.

This project focuses on understanding low-level data structure mechanics including dynamic memory allocation, pointer manipulation, and modular object-oriented design.

---

## Project Overview

The goal of this implementation is to strengthen foundational knowledge of core data structures by designing them manually using C++ templates.

Each data structure is implemented using generic programming (`template <class T>`), allowing it to work with multiple data types such as:

- int
- float
- char
- double
- user-defined objects
---

## Implemented Data Structures

| Data Structure | Class Name | Characteristics |
|---------------|------------|----------------|
| Singly Linear Linked List | `SinglyLLL<T>` | Forward traversal |
| Singly Circular Linked List | `SinglyCLL<T>` | Circular forward linking |
| Doubly Linear Linked List | `DoublyLLL<T>` | Bidirectional traversal |
| Doubly Circular Linked List | `DoublyCLL<T>` | Circular bidirectional linking |
| Stack | `Stack<T>` | LIFO principle |
| Queue | `Queue<T>` | FIFO principle |

---

## Core Features

- Generic template-based architecture  
- Modular separation of Node and Container classes  
- Position-based insertion and deletion  
- Circular and linear structure handling  
- O(1) element counting using internal counter  
- Dynamic memory allocation using `new` and `delete`  
- Visual `Display()` representation of structures  

---

## Design Architecture

Each data structure follows a two-layer design:

### Node Class
Responsible for:
- Storing data  
- Managing pointer links (`next` / `prev`)  

### Container Class
Responsible for:
- Insert / Delete operations  
- Traversal logic  
- Size tracking  
- Structural integrity  

---

## Time Complexity Analysis

| Operation | Complexity |
|-----------|------------|
| InsertFirst | O(1) |
| DeleteFirst | O(1) |
| InsertLast (Singly Linear) | O(n) |
| InsertLast (Circular / Doubly) | O(1) |
| InsertAtPos | O(n) |
| DeleteAtPos | O(n) |
| Stack Push / Pop | O(1) |
| Queue Enqueue / Dequeue | O(1) |
| Count | O(1) |

---

## 👤 Author
### Rucha Hanumant Pawar.
