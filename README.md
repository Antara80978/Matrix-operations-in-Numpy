# Task 14 - NumPy Matrix Operations

## AI & ML Internship

### Objective

The objective of this task is to create two matrices and perform basic matrix operations using NumPy.

### Tools and Technologies

* Python
* NumPy
* Jupyter Notebook

### Description

In this task, two matrices were created using NumPy arrays. Basic matrix operations such as addition, subtraction, matrix multiplication and transpose were performed.

### Operations Performed

1. **Matrix Addition:** Adds the corresponding elements of two matrices.
2. **Matrix Subtraction:** Subtracts the corresponding elements of the second matrix from the first.
3. **Matrix Multiplication:** Multiplies the rows of the first matrix by the columns of the second matrix and calculates their sums.
4. **Matrix Transpose:** Converts the rows of a matrix into columns and its columns into rows.

### Code

```python
import numpy as np

A = np.array([[1, 2, 3],
              [4, 5, 6],
              [7, 8, 9]])

B = np.array([[9, 8, 7],
              [6, 5, 4],
              [3, 2, 1]])

print("Matrix A:\n", A)
print("Matrix B:\n", B)

print("Addition:\n", A + B)
print("Subtraction:\n", A - B)
print("Matrix Multiplication:\n", A @ B)
print("Transpose of A:\n", A.T)
print("Transpose of B:\n", B.T)
```

### Conclusion

Successfully created two matrices and performed addition, subtraction, matrix multiplication and transpose operations using NumPy. This task helped me understand basic matrix operations and their applications in machine learning.
