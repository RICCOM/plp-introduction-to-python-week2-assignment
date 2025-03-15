# Python List Manipulation 🐍

## Overview
This script demonstrates basic **list operations** in Python, including:
- Creating an empty list
- Adding elements using `append()`
- Inserting an element at a specific position
- Extending a list with another list
- Removing the last element using `pop()`
- Sorting the list in ascending order
- Finding the index of a specific value

## Steps Performed in the Script
1. **Create an empty list** called `my_list`.
2. **Append** elements `10, 20, 30, 40` to the list.
3. **Insert** the value `15` at the second position.
4. **Extend** `my_list` with another list `[50, 60, 70]`.
5. **Remove** the last element from `my_list`.
6. **Sort** `my_list` in ascending order.
7. **Find and print** the index of the value `30`.

## Code Implementation
```python
# Step 1: Create an empty list
my_list = []

# Step 2: Append elements 10, 20, 30, 40
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

# Step 3: Insert the value 15 at the second position (index 1)
my_list.insert(1, 15)

# Step 4: Extend my_list with another list [50, 60, 70]
my_list.extend([50, 60, 70])

# Step 5: Remove the last element from my_list
my_list.pop()

# Step 6: Sort my_list in ascending order
my_list.sort()

# Step 7: Find and print the index of the value 30
index_of_30 = my_list.index(30)
print("Index of 30:", index_of_30)

# Print final list to check the result
print("Final List:", my_list)
