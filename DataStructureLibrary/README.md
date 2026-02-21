# Generalized Data Structure Library (C++)

This project contains a generic implementation of fundamental linear data structures in C++ using templates.  
The main objective was to understand the internal working of commonly used data structures by implementing them from scratch without using STL containers.

The implementation focuses on pointer manipulation, dynamic memory handling, and reusable design through generic programming.

## Implemented Data Structures

### Linked Lists
- Singly Linear Linked List
- Singly Circular Linked List
- Doubly Linear Linked List
- Doubly Circular Linked List

Supported operations:
- InsertFirst / InsertLast
- DeleteFirst / DeleteLast
- InsertAtPos
- DeleteAtPos
- Display
- Count (O(1))

---

### Stack (LIFO)
Implemented using linked list structure.

Operations:
- push()
- pop()
- peep()
- Display()
- Count()

---

### Queue (FIFO)
Implemented using first and last pointers.

Operations:
- enqueue()
- dequeue()
- Display()
- Count()

---

## Technical Concepts Used

- C++ Templates (Generic Programming)
- Object Oriented Design
- Dynamic Memory Allocation (`new` / `delete`)
- Pointer traversal and node linking
- Circular and doubly linked structures
- Time complexity tracking using node counter

---

## Design Approach

Each data structure is divided into:

- **Node Class** → stores data and pointer links  
- **Functionality Class** → handles operations and logic

This separation keeps the design modular and reusable.

---

## Complexity Summary

| Operation | Complexity |
|-----------|------------|
| InsertFirst | O(1) |
| DeleteFirst | O(1) |
| InsertLast (Singly LL) | O(n) |
| InsertLast (Circular / Doubly) | O(1) |
| InsertAtPos | O(n) |
| DeleteAtPos | O(n) |
| Stack Push / Pop | O(1) |
| Queue Enqueue / Dequeue | O(1) |
| Count | O(1) |

---
