# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Algorithm:

### Step 1: 
Import the numpy library and set OPENBLAS_NUM_THREADS = "1" to prevent runtime errors.

### Step 2: 
Define the 3×3 matrix A using np.array() with the values [[3, 2, 5], [1, 1, 2], [3, 3, 6]].

### Step 3: 
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix and store it in the variable 'rank'.

### Step 4: 
Print the rank of the matrix using print(). 
## Program:
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"

import numpy as np

A = np.array([[3, 2, 5],[1, 1, 2],[3, 3, 6]])

rank = np.linalg.matrix_rank(A)
print( rank)
## Output:
<img width="694" height="581" alt="{875A7820-C5AA-41F6-B4E2-F204AA6EB6F0}" src="https://github.com/user-attachments/assets/f15116d0-2def-4dbd-bb08-8020fc2b4be8" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

