# 🚀 Customised Virtual File System (CVFS)

![C](https://img.shields.io/badge/C-Language-blue?style=for-the-badge&logo=c&logoColor=white)
![System Programming](https://img.shields.io/badge/System-Programming-orange?style=for-the-badge)
![Linux File System](https://img.shields.io/badge/Linux-File%20System-yellow?style=for-the-badge)
![OS Concepts](https://img.shields.io/badge/Operating%20System-Internals-blueviolet?style=for-the-badge)

---

## 🧩 Project Overview

This project is a **custom implementation of a Virtual File System (VFS)** that simulates the core functionality of the **Linux File System**.

It is built entirely in **C Programming**, with its own **custom shell** to interact with the virtual environment.

The project provides practical understanding of:

- System Calls  
- File Handling  
- Memory Management  
- Operating System Internals  

---

## ✨ Key Features

### 🔹 Custom Shell Interface
- Provides Linux-like commands for file operations:
  - create  
  - open  
  - read  
  - write  
  - delete  
  - ls  

---

### 🔹 System Call Simulation
Implements core Linux file system calls using C:
creat, read, write, lseek, stat, fstat, unlink, ls

---

### 🔹 File System Data Structures

- Incore Inode Table  
- File Table  
- UAREA (User Area)  
- User File Descriptor Table  

---

### 🔹 Platform Independent
- Allows Linux-style file handling functionalities to work on **any operating system platform**.

---

### 🔹 Database-like Functionality
- Provides a customised data management layer with structured file handling.

---

## 🎯 Learning Outcomes

- Deep understanding of **Linux File System internals**
- Practical knowledge of **OS Data Structures**
  - Inode
  - File Tables
  - UAREA
- Strong grasp of **System Programming in C**
- Hands-on experience with **Shell Design & Command Interpreter**
- Application of **low-level logic building**

---
## ▶️ Example Usage

```bash
$ ./Myexe

\ CVFS : > creat Demo.txt 3
File gets succesfully created with FD 3

\ CVFS : > write 3
Enter the data that you want to write :
Hello CVFS
10 bytes gets succesfully written

\ CVFS : > read 3 5
Read operation is succesful
Data from file is : Hello

\ CVFS : > ls
3   Demo.txt   10

\ CVFS : > unlink Demo.txt
File gets succesfully deleted

\ CVFS : > exit
```

## 👤 Author
### Rucha Hanumant Pawar.



