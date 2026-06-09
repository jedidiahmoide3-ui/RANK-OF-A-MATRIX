# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Start and input the order and elements of the matrix.
### Step 2: Perform row operations to convert the matrix into row echelon form.
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: Display the rank of the matrix and stop.
## Program:
#Program to find the rank of a matrix.
#Developed by: Jedidiah M D
#RegisterNumber: 212225230116
```
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrixa=([[3,2,5],[1,1,2],[3,3,6]])
result=np.linalg.matrix_rank(matrixa)
print(result)
```
## Output:
<img width="232" height="131" alt="image" src="https://github.com/user-attachments/assets/a6ff5bf5-7fa6-4432-8a61-88367c1f117a" />


## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

