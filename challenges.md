## Coding Challenge Problems

### Easy

Problem: reverse a string.

Python solution:
```python
def reverse(s):
  if s == "":
    return ""
  else:
    return (reverse(s[1:]) + s[0])
```
