# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import numpy as library
### Step 2:  Use eig(A) function to find
        eigenvalues and eigenvectors
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: end the program

## Program:
<img width="822" height="83" alt="Screenshot 2026-05-14 111119" src="https://github.com/user-attachments/assets/505d4ee4-3fab-4aaa-acd5-db727445da6e" />
```
#Program to find the eigen values and eigen vectors.
#Developed by: MOHAMED AATHIL M
#RegisterNumber:212225040246

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np


import numpy as np

a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])

values,vectors = np.linalg.eig(a)

print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:
<img width="1280" height="228" alt="Screenshot 2026-05-14 111103" src="https://github.com/user-attachments/assets/75026760-66a1-446e-84b3-7240cdff8dff" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
