# Data Structures - Exercise 1 & 2

This repository contains code from **Data Structures & Algorithm** Labs. The following labs include the implementation of basic data structures like **Queue**, **Linked List**, and the usage of the **deque** from Python's `collections` module.

## Exercise 1 - Queue Implementation

In Exercise 1, we implemented a **Queue** data structure. The code demonstrates the following:

- **Queue** class with:
  - `enqueue(data)` - Adds an element to the end of the queue.
  - `dequeue()` - Removes the element from the front of the queue.
  - `isempty()` - Checks if the queue is empty.

The code also demonstrates the use of Python's **deque** for queue-like operations, such as adding and removing elements from both ends.

### Key Functions in Lab 05:
- `enqueue()`
- `dequeue()`
- `isempty()`
- Operations using **collections.deque** like `append()`, `appendleft()`, `pop()`, `popleft()`, and `clear()`.

## Exercise 2 - Linked List Implementation

In Exercise 2, we implemented a **Singly Linked List**. The following operations are performed:

- **Linked List** class with the following methods:
  - `append(data)` - Adds a node with the specified data at the end of the list.
  - `display()` - Displays all elements in the linked list.
  - `delete()` - Deletes the last node in the list.
  - `length()` - Returns the length of the list.
  - `insert(data, index)` - Inserts a new node at a specific index.
  - `appendbefore(data)` - Adds a node at the beginning of the list.

### Key Functions in Lab 06:
- `append()`
- `delete()`
- `display()`
- `length()`
- `insert()`
- `appendbefore()`

## Technologies Used

- **Python**: Used to implement the Queue and Linked List data structures.
- **collections.deque**: A deque is used to demonstrate efficient operations on both ends of the list.
