---
author: enki-ai
type: normal
category: must-know
links:
  - >-
    [Array Reshaping](https://numpy.org/doc/stable/reference/generated/numpy.reshape.html){website}
practiceQuestion:
  formats:
    - fill-in-the-gap
  context: standalone
revisionQuestion:
  formats:
    - fill-in-the-gap
  context: standalone
---

# Reshaping Arrays

---

## Content

You can change an array's shape without changing its data:

Convert 1D to 2D array:

```python
arr = np.array([1, 2, 3, 4])
reshaped = arr.reshape(2, 2)
# array([[1, 2],
#        [3, 4]])
```

> 💡 The total number of elements must stay the same!

Make array flat (1D):

```python
matrix = np.array([[1, 2], [3, 4]])
flat = matrix.flatten()
# array([1, 2, 3, 4])
```

Reverse dimensions:

```python
arr = np.array([[1, 2], [3, 4]])
transposed = arr.T
# array([[1, 3],
#        [2, 4]])
```

---

## Practice

Reshape a 1D array into a 2x2 matrix:

```python
arr = np.array([1, 2, 3, 4])
matrix = arr.???(2, ???)
```

- `reshape`
- `2`
- `shape`
- `4`

---

## Revision

To make a 2D array into a 1D array, use:

???

- `flatten()`
- `flat()`
- `reshape(1)`
- `1D()`
