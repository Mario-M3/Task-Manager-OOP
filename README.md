# Object-Oriented Task Management System

A lightweight, object-oriented Python application designed to demonstrate software architecture fundamentals, state tracking, and type safety.

## Key Features
* **Encapsulated Task Logic**: Uses dedicated domain objects (`Task`) to manage lifecycle transitions ("To Do" -> "In Progress" -> "Complete").
* **Efficient Lookups**: Leverages a dictionary-backed `TaskManager` for $O(1)$ task retrieval by ID.
* **Type Annotations**: Implements native Python type hints (`typing.Dict`, `typing.Optional`) for robust code maintenance.

## How to Run
```bash
python task_manager.py

Sample Output
Plaintext

=== TASK MANAGEMENT SYSTEM OUTPUT ===
==============================
ID:          101
Description: Setup Database Schema
Status:      In Progress
Assigned To: Alice
==============================
