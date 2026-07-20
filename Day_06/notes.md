# Day 06 Notes

## Concepts Learned

- List Comprehensions
- Nested Iteration
- Conditional Filtering
- 3D Coordinate Generation
- Python Lists

---

## Solution Approach

Instead of writing three nested loops, Python allows us to write everything in a single list comprehension.

```python
result = [
    [i, j, k]
    for i in range(x + 1)
    for j in range(y + 1)
    for k in range(z + 1)
    if i + j + k != n
]
```

The condition:

```python
if i + j + k != n
```

filters out unwanted coordinates.

---

## Time Complexity

O((x + 1) × (y + 1) × (z + 1))

Every possible coordinate is evaluated once.

---

## Space Complexity

O(m)

where **m** is the number of valid coordinates stored in the output list.

---

## Key Takeaway

List comprehensions provide a concise and Pythonic way to:

- Generate lists
- Replace nested loops
- Apply conditions while creating collections

They improve code readability and are widely used in professional Python development.

---

## Real-World Relevance

List comprehensions are frequently used in:

- Network Automation
- API response processing
- Filtering device inventories
- Data transformation
- Cloud resource management
- Parsing JSON and YAML files

They make automation scripts shorter, cleaner, and easier to maintain.
