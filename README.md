# Java Collections Examples

This repository contains two simple Java examples demonstrating the usage of `ArrayList` and `HashMap` from the Java Collections Framework. These examples showcase basic operations such as adding, retrieving, iterating, and removing elements in these data structures.

---

## Files

### 1. **ArrayListExample.java**
- **Purpose**: Demonstrates how to use an `ArrayList` to store and manage a collection of fruit names.
- **Features**:
  - Adds elements to the `ArrayList`.
  - Retrieves elements using a for-each loop.
  - Accesses an element by its index.
  - Removes an element from the `ArrayList`.
- **Key Methods**:
  - `add(E e)`: Adds an element to the list.
  - `get(int index)`: Retrieves an element by its index.
  - `remove(Object o)`: Removes the first occurrence of the specified element.

#### Example Output

### 2. **HashMapExample.java**
- **Purpose**: Demonstrates how to use a `HashMap` to store and manage key-value pairs (names and ages in this case).
- **Features**:
  - Adds key-value pairs to the `HashMap`.
  - Retrieves a value using a key.
  - Iterates over the `HashMap` using its keys.
  - Removes a key-value pair.
- **Key Methods**:
  - `put(K key, V value)`: Adds a key-value pair to the map.
  - `get(Object key)`: Retrieves the value associated with the specified key.
  - `remove(Object key)`: Removes the mapping for the specified key.

#### Example Output

---

## How to Run

1. Compile the files using `javac`:
   ```bash
   javac ArrayListExample.java
   javac HashMapExample.java
