#  Python Lists

Lists are used to store multiple items in a single variable. They are one of 4 built-in data structures in Python used to store collections of data.

### Key Characteristics:
* **Ordered:** Items have a defined order that will not change.
* **Mutable:** You can change, add, and remove items after creation.
* **Allow Duplicates:** Since lists are indexed, they can have items with the same value.

---

## Basic Operations

```python
# Creation
fruits = ["apple", "banana", "cherry"]

# Accessing (Indexing)
print(fruits[0])   # "apple"
print(fruits[-1])  # "cherry" (last item)

# Modification
fruits[1] = "blueberry"
```
## List Sclicing
Extracting a part of the list: list[start:stop:step]
```python
nums = [0, 1, 2, 3, 4, 5]
print(nums[1:4])  # [1, 2, 3]
print(nums[:3])   # [0, 1, 2] (from start)
print(nums[::2])  # [0, 2, 4] (every second element)
```

## List Methods Reference

| Method | Description | Example |
| :--- | :--- | :--- |
| **`.append(x)`** | Adds an item to the end of the list | `list.append("orange")` |
| **`.insert(i, x)`** | Adds an item at a specific index `i` | `list.insert(1, "mango")` |
| **`.remove(x)`** | Removes the first occurrence of value `x` | `list.remove("apple")` |
| **`.pop(i)`** | Removes and returns the item at index `i` (default is last) | `list.pop(0)` |
| **`.sort()`** | Sorts the list in ascending order (in-place) | `list.sort()` |
| **`.reverse()`** | Reverses the elements of the list (in-place) | `list.reverse()` |
| **`.extend(coll)`** | Appends all elements from another collection | `list.extend([1, 2])` |
| **`.clear()`** | Removes all items from the list | `list.clear()` |
