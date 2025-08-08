# List Operations in Python

## Overview
This Python program demonstrates common list operations, including:

- Creating a list
- Appending elements
- Inserting at a specific position
- Extending with another list
- Removing elements
- Sorting the list
- Finding the index of a specific value

The code is **beginner-friendly** and provides an easy introduction to Python list manipulation.

---

## Features

### 1. Create an Empty List
Initializes a new list called `my_list`.

```python
my_list = []
```

### 2. Append Elements
Adds the values `10`, `20`, `30`, and `40` to `my_list`.

```python
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)
```

### 3. Insert at a Specific Position
Inserts the value `15` at the second position (index `1`).

```python
my_list.insert(1, 15)
```

### 4. Extend the List
Extends `my_list` with `[50, 60, 70]`.

```python
my_list.extend([50, 60, 70])
```

### 5. Remove the Last Element
Uses `.pop()` to remove the last item.

```python
my_list.pop()
```

### 6. Sort the List
Sorts the list in ascending order.

```python
my_list.sort()
```

### 7. Find the Index of a Value
Finds and prints the index of `30` in `my_list`.

```python
index_of_30 = my_list.index(30)
print("Index of 30:", index_of_30)
```

---

## Example Output
```
Index of 30: 3
```

---

## How to Run
1. Save the code into a file called `list_operations.py`.
2. Open your terminal or command prompt.
3. Run:
   ```bash
   python list_operations.py
   ```
