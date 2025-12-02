

#### **Introduction to NumPy**

**NumPy (Numerical Python)** is a powerful Python library designed for efficient numerical computation. It provides support for **multi-dimensional arrays**, **mathematical operations**, and **vectorized computations**, making it much faster and more memory-efficient than Python’s built-in lists. NumPy is widely used in data science, machine learning, scientific computing, and data analysis.



#### **NumPy vs Python List**

##### **NumPy**

* Optimized for numerical and scientific operations
* Stores elements in **contiguous memory**, improving speed
* Supports **multi-dimensional arrays (ndarrays)**
* Enables **vectorized operations**, which eliminate the need for explicit loops

##### **Python List**

* General-purpose and flexible
* Slower for numerical tasks
* Does not support mathematical operations directly
* Not memory-efficient for large-scale computations



#### **NumPy Array Creation**

##### **`np.array()`**

Creates a NumPy array from a Python list or nested list.

```python
import numpy as np
arr = np.array([1, 2, 3])
```



#### **Iteration in NumPy**

##### **Basic Iteration**

You can loop through array elements, but NumPy is optimized for **vectorized operations**, which are faster and preferred over loops.

##### **`np.nditer()`**

Used to iterate efficiently over multi-dimensional arrays.

```python
for x in np.nditer(arr):
    print(x)
```



#### **Slicing in NumPy**

Slicing allows you to extract a subset of elements from a NumPy array.
The general syntax is:

```
array[start : stop : step]
```

##### **1D Array Slicing**

Used to retrieve a range of elements:

* **Start** → beginning index (inclusive)
* **Stop** → ending index (exclusive)
* **Step** → interval between elements

Example:

```python
arr[1:4]   # elements at index 1, 2, 3
```



##### **2D Array Slicing**

In 2D arrays, you specify slices for both **rows** and **columns**:

```
array[row_start:row_end , col_start:col_end]
```

Example:

```python
arr[1:3, 0:2]   # rows 1–2, columns 0–1
```

##### **Negative Indexing**

You can also slice using negative indexes (e.g., `-1` refers to the last element).




