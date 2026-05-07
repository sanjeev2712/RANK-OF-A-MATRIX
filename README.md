# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the required libraries.
### Step 2: Set the OpenBLAS thread limit.
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: End the program


## Program:
```
#Program to find the rank of a matrix.
#Developed by: Sanjeev Kumar .K
#RegisterNumber:212225230246
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrixA=np.array([[3,2,5],[1,1,2],[3,3,6]])
rank=np.linalg.matrix_rank(matrixA)
print(rank)
```
## Output:
<img width="1476" height="839" alt="Screenshot 2026-05-02 081445" src="https://github.com/user-attachments/assets/d89d1bbe-1622-4283-abe9-e87fec8505bb" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

