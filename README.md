# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the required NumPy library using import numpy as np.
### Step 2: 
Define the matrix as a NumPy array (example: A = np.array([[1, 2, 3], [3, 6, 9]])).
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
Store the result in a variable (e.g., rank) and display the rank of the matrix using the print() function.
## Program:
```python
import numpy as np
A = np.array([[3, 2, 5],
              [1, 1, 2],
              [3, 3, 6]])

rank = np.linalg.matrix_rank(A)
print( rank)

```
## Output:
<img width="1380" height="370" alt="image" src="https://github.com/user-attachments/assets/291ae620-81d0-4046-84a1-6fadbc1d9b16" />


## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

