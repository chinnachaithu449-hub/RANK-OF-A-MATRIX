# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
 Step 1: Step 1: Import the required library numpy as np.
Step 2: Define the matrix as a 2D NumPy array with the given elements.
Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
Step 4: Print the rank of the matrix. 
## Program:
~~~
#Program to find the rank of a matrix.

#Developed by: G chaithanya

#RegisterNumber: 212225230087

import os

os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

A = np.array([ [5, -3, -10], [2, 2, -3], [-3, -1, 5] ])

rank = np.linalg.matrix_rank(A)

print(rank)
~~~
## Output:
<img width="790" height="822" alt="{27F1F203-C110-481C-B16C-F2987DF812C5}" src="https://github.com/user-attachments/assets/a881e61e-df99-44d7-ba60-3e243d697793" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

