# Introduction to NumPy Basics 

Welcome to the **NumPy Basics** repository. This repository serves as a beginner-friendly guide to understanding the most important and fundamental concepts of the NumPy library in Python. 🚀

## Description 

This repository is designed to help beginners learn the basics of NumPy, a fundamental package for scientific computing with Python. NumPy provides powerful data structures, implementing multi-dimensional arrays and matrices, along with a collection of mathematical functions to operate on these arrays. ✍️

## Notebooks  

The repository contains a series of Jupyter Notebooks, each covering a specific topic related to NumPy basics. These notebooks are organized topic-wise, making it easy for learners to follow along and grasp the concepts progressively. 

Feel free to explore the notebooks 📒 in the following order:

### [01 Introduction to NumPy.ipynb](01_lists_np_arrays.ipynb)

**Topics Covered:**
- **Difference between Python list and NumPy array:** This section explores the fundamental differences between Python lists and NumPy arrays, highlighting the advantages of using NumPy arrays for numerical computations. 📊

- **Array Declaration:** Understand the syntax and parameters involved in array creation. 📝

- **Array Attributes:** Explore the attributes associated with NumPy arrays, such as shape, size, dimensionality, data type, etc.📏

- **Interconversion of list and array:** Discover how to convert Python lists to NumPy arrays and vice versa. 🔃


### [02 Array Creation and Shape Operations](02_np_array_creations_and_shape_operations.ipynb)
_
**Topics Covered:**
- **Array Creation:** Explore various methods for creating NumPy arrays, including `numpy.array()`, `numpy.zeros()`, `numpy.ones()`, `numpy.empty()`, `numpy.arange()`, and `numpy.linspace()`. Understand the purpose and usage of each method in array creation. 🌱

- **Shape Operations:** Learn about shape operations that allow you to manipulate the dimensions and structure of NumPy arrays. Topics include usage of `shape`, `flatten`, `ravel`,`resize`,`transpose` and `flat`. 🔄

### [03 Array Slicing and Indexing](03_np_array_indexing_and_slicing.ipynb)

**Topics Covered:**
- **Array Indexing:** Understand the various indexing methods, including integer indexing, negative indexing, and boolean indexing. 🔍

- **Array Slicing:** Learn about array slicing in NumPy, which involves extracting a subset of elements from a NumPy array based on specified start, stop, and step parameters. 🍰

### [04 Elementwise Operations](04_np_elementwise_operations.ipynb)

**Topics Covered:**
- **Elementwise Operations:** Explore the concept of elementwise operations, which involve performing arithmetic operations (addition, subtraction, multiplication, division, exponentiation, etc.) on corresponding elements of NumPy arrays. ➕➖✖️➗

- **Matrix Multiplication:** Learn about matrix multiplication in NumPy, which involves multiplying two matrices to produce a new matrix. Understand the usage of the `numpy.matmul()` function for performing matrix multiplication. ⚙️

- **Dot Product:** Explore the concept of the dot product, which is a specific type of matrix multiplication that results in a scalar value using `numpy.dot()` function. 🔵

### [05 Reduction Methods](05_np_reduction_methods.ipynb)

**Topics Covered:**
- **Reduction Methods:** Explore reduction operations in NumPy, which are functions that typically collapse the array along one or more dimensions, resulting in a reduced size or a scalar value. This notebook covers the following reduction methods:
  - `sum` and `prod`: Compute the sum and product of array elements along specified axes.
  - `min` and `max`: Find the minimum and maximum values in an array along specified axes.
  - `argmin` and `argmax`: Find the indices of the minimum and maximum values in an array along specified axes.
  - `cumsum` and `cumprod`: Compute the cumulative sum and cumulative product along specified axes.
  - `mean`, `std`, and `var`: Compute the mean, standard deviation, and variance of array elements along specified axes.
  - `ptp`: Compute the peak-to-peak (maximum - minimum) value along specified axes.
  - `any` and `all`: Check if any or all elements along specified axes evaluate to True.📉📈

### [06 Universal Functions](06_np_universal_functions.ipynb)

**Topics Covered:**
- **Universal Functions (ufuncs):** Explore different types of universal functions (ufuncs) in NumPy, which are functions that operate element-wise on NumPy arrays. This notebook covers the following types of ufuncs:
  - **Mathematical:** Includes functions for basic arithmetic operations such as addition, subtraction, multiplication, division, exponentiation, etc. ➕➖✖️➗
  - **Comparison:** Includes functions for element-wise comparison operations such as greater than, less than, equal to, not equal to, etc. 🔄
  - **Logical:** Includes functions for element-wise logical operations such as logical AND, logical OR, logical NOT, etc. ⚠️
  - **Bitwise:** Includes functions for element-wise bitwise operations such as bitwise AND, bitwise OR, bitwise XOR, bitwise NOT, etc. 🔣
  - **Trigonometric:** Includes functions for element-wise trigonometric operations such as sine, cosine, arcsine, arccosine, arctangent, etc. 📐
  - **Miscellaneous:** Includes other miscellaneous functions such as absolute value, square root, exponential, logarithm, rounding, etc.🔍

### [07 Broadcasting in NumPy](07_broadcasting.ipynb)

**Topics Covered:**

- **Broadcasting in NumPy:** This notebook covers the broadcasting technique in NumPy, which allows arrays of different shapes to be combined in arithmetic operations. Broadcasting effectively extends the smaller array to match the shape of the larger array, enabling element-wise operations to be performed smoothly. 📡

