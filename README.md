# ImplementCustomIterator

A Java project demonstrating the implementation of a **custom list class** (`DefaultMyList`) and a **custom iterator** to traverse and manipulate list elements.  
This project showcases an in-depth understanding of **data structures**, **iterators**, and **custom collection behavior** in Java — implemented without using built-in list classes like `ArrayList` or `LinkedList`.

---

## 📘 Description

The project defines a custom interface `MyList`, extending Java’s `Iterable` interface. It provides a blueprint for basic list operations such as `add`, `remove`, `clear`, `contains`, and `toArray`.  
The `DefaultMyList` class implements `MyList` using a **doubly linked list** data structure and provides a nested `IteratorImpl` class that supports safe element iteration and removal.

This implementation simulates the internal behavior of standard Java collections, making it a great exercise for understanding **how Java Collections Framework works internally**.

---

## 🚀 Features

- Custom doubly linked list implementation.  
- Fully functional custom iterator with `hasNext()`, `next()`, and `remove()` methods.  
- Safe element removal during iteration.  
- Methods for:
  - Adding elements
  - Removing elements by object or index
  - Checking if elements exist
  - Converting to array
  - Clearing the list  
- Internal node management for optimized navigation between elements.

---

## 🧩 Class Overview

### 🔹 `MyList` (Interface)
Defines the structure of a custom list, including methods:
- `add(Object e)`
- `remove(Object o)`
- `clear()`
- `contains(Object o)`
- `containsAll(MyList c)`
- `toArray()`
- `size()`

### 🔹 `DefaultMyList` (Implementation)
Implements `MyList` using a **doubly linked list** and an **inner iterator** class:
- Manages `Node` objects containing `data`, `next`, and `previous` references.
- Supports bidirectional traversal for efficiency.

### 🔹 `IteratorImpl` (Inner Class)
Custom implementation of the `Iterator` interface providing:
- Sequential access to list elements.
- Safe removal of elements during iteration.

---

## 🧠 Learning Outcomes

Through this project, you will learn:
- How to create and manage **custom data structures**.
- How to implement **iterators** manually.
- How to maintain **internal node linking** for lists.
- How Java handles **`Iterator.remove()`** safely.
- The importance of **encapsulation** and **inner classes** in Java.

---

## 🛠️ Technologies Used

- **Language:** Java  
- **IDE:** Eclipse IDE  
- **JDK Version:** 17+  
- **Concepts:** Iterable, Iterator, LinkedList structure, Encapsulation  

---

