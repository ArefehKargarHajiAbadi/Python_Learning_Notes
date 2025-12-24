# Data Structures: Strings 

Strings in Python are sequences of Unicode characters. They are one of the most used data types and are **immutable** (cannot be changed after creation).

---

## 1. String Slicing & Indexing
Accessing parts of a string is done using the `[start:stop:step]` syntax.



| Feature | Syntax | Example (`s = "Python"`) | Result |
| :--- | :--- | :--- | :--- |
| **First Character** | `s[0]` | `s[0]` | `'P'` |
| **Last Character** | `s[-1]` | `s[-1]` | `'n'` |
| **Slicing** | `s[start:stop]` | `s[0:2]` | `'Py'` |
| **Step** | `s[::step]` | `s[::2]` | `'Pto'` |
| **Reverse** | `s[::-1]` | `s[::-1]` | `'nohtyP'` |

---

## 2. Essential Methods
Python provides a rich set of built-in methods to manipulate strings.

| Method | Description | Return Type |
| :--- | :--- | :--- |
| `.upper()` / `.lower()` | Changes the case of the string | `str` |
| `.strip()` | Removes leading/trailing whitespace | `str` |
| `.split(sep)` | Splits string into a list based on `sep` | `list` |
| `.join(iterable)` | Joins list elements into a single string | `str` |
| `.replace(old, new)` | Replaces occurrences of a substring | `str` |
| `.find(sub)` | Returns index of first occurrence of `sub` | `int` |
| `.isdigit()` | Returns `True` if string contains only digits | `bool` |



---

## 3. Formatting (f-strings)
F-strings are the preferred way to format strings in modern Python (3.6+).

```python
name = "Gemini"
version = 3.0
print(f"Hello, I am {name} version {version:.1f}")
