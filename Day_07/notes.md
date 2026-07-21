# Day 07 Notes

## Concepts Learned

- Functions
- Boolean Values
- if-elif-else
- Modulo Operator (%)
- Return Statement

---

## Solution Approach

A leap year follows these rules:

1. Divisible by 400 → Leap Year
2. Divisible by 100 → Not a Leap Year
3. Divisible by 4 → Leap Year
4. Otherwise → Not a Leap Year

Example:

```python
if year % 400 == 0:
    return True
elif year % 100 == 0:
    return False
elif year % 4 == 0:
    return True
else:
    return False
```

---

## Time Complexity

O(1)

Only a fixed number of arithmetic operations are performed.

---

## Space Complexity

O(1)

No extra memory is used.

---

## Key Takeaway

This challenge introduces writing reusable Python functions and returning Boolean values instead of printing results directly.

It also reinforces the importance of evaluating multiple conditions in the correct order.

---

## Real-World Relevance

Conditional logic like this is widely used in:

- Network Automation scripts
- Configuration validation
- API response handling
- Data filtering
- Security policy evaluation
- Infrastructure automation
