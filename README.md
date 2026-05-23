# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
### Step 2: 
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
## Program:


import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"

import numpy as np

A = np.array([[3, 2, 5],[1, 1, 2],[3, 3, 6]])

rank = np.linalg.matrix_rank(A)
print("Rank of the matrix:", rank)
## Output:
<img width="473" height="789" alt="{D465487A-AF18-4EED-9C10-A5AC4567585A}" src="https://github.com/user-attachments/assets/43fa69ac-fcc5-448c-bf9c-3386b386abe7" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

