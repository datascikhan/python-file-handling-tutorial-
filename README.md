

# Python File Handling Tutorial 📂🐍

Learn **Python File Handling** step by step! This tutorial covers **creating, reading, writing, appending, and managing files** using Python. Perfect for **beginners, students, and developers** who want to master file operations efficiently.

---

## 📌 Table of Contents

1. [Introduction](#introduction)
2. [File Operations Overview](#file-operations-overview)
3. [File Modes](#file-modes)
4. [Reading Files](#reading-files)
5. [Writing Files](#writing-files)
6. [Appending Files](#appending-files)
7. [Using with Statement](#using-with-statement)
8. [Other Useful Methods](#other-useful-methods)
9. [Examples](#examples)
10. [Resources](#resources)

---

## Introduction

**File Handling in Python** allows programs to **create, read, write, update, and manage files**.  
With file handling, you can **store data permanently** or retrieve it when needed.

Common operations include:
- **Open** – Access a file
- **Read** – Read file content
- **Write** – Write content to a file
- **Append** – Add content to the end of a file
- **Close** – Close the file safely

---

## File Operations Overview

| Operation      | Function / Mode                                    | Description                          |
| -------------- | -------------------------------------------------- | ------------------------------------ |
| Open file      | `open(filename, mode)`                             | Access a file                         |
| Read file      | `file.read() / file.readline() / file.readlines()` | Read file content                     |
| Write file     | `file.write()`                                     | Write new content                     |
| Append file    | `file.write()` with `'a'` mode                     | Add content to file end               |
| Close file     | `file.close()`                                     | Close file                             |
| With statement | `with open() as file:`                             | Automatically open and close file     |

---

## File Modes

| Mode   | Description                      |
| ------ | -------------------------------- |
| `'r'`  | Read only (default)              |
| `'w'`  | Write only (overwrite if exists) |
| `'a'`  | Append only (add at end)         |
| `'r+'` | Read and write                   |
| `'rb'` | Read binary                      |
| `'wb'` | Write binary                     |
| `'ab'` | Append binary                    |

---

## Reading Files

Read a file's content using **`"r"` mode**.  

```python
with open("example.txt", "r") as file:
    content = file.read()
    print(content)


























python, python-file-handling, file-operations, python-tutorial, python-beginner, python-files, read-write-files

