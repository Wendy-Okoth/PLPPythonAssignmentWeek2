# PLPPythonAssignmentWeek2
# Week Two Python Assignment

## Description
This assignment demonstrates Python list operations including:
- Creating and modifying lists
- Inserting and appending values
- Extending lists with another list
- Removing elements
- Sorting
- Finding the index of an element

## Steps Performed
1. **Create an empty list** named `my_list`.
2. **Append** the values `10`, `20`, `30`, and `40` to `my_list`.
3. **Insert** the value `15` at the second position (index `1`).
4. **Extend** the list by adding another list `[50, 60, 70]`.
5. **Remove** the last element using `.pop()`.
6. **Sort** the list in ascending order using `.sort()`.
7. **Find and print** the index of the value `30`.

## Code Example
```python
# Step 1: Create an empty list
my_list = []

# Step 2: Append elements 10, 20, 30, 40
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

# Step 3: Insert 15 at the second position (index 1)
my_list.insert(1, 15)

# Step 4: Extend the list with [50, 60, 70]
my_list.extend([50, 60, 70])

# Step 5: Remove the last element
my_list.pop()

# Step 6: Sort the list in ascending order
my_list.sort()

# Step 7: Find and print the index of value 30
index_of_30 = my_list.index(30)

# Display the results
print("Final List:", my_list)
print("Index of 30:", index_of_30)

Expected Output
Final List: [10, 15, 20, 30, 40, 50, 60]
Index of 30: 3

