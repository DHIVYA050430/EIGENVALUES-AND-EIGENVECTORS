# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
import the numpy module to use the built-in functions for calculation
### Step 2:
Get the input matrix from the user
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
End the program

## Program:
#Program to find the eigen values and eigen vectors.

#Developed by: DIVYA E

#RegisterNumber: 23011187

import numpy as np

A = np.array([[2,2],[1,3]])

values,vectors=np.linalg.eig(A)

print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))

## Output:
```
![OUTPUT](https://github.com/DHIVYA050430/EIGENVALUES-AND-EIGENVECTORS/assets/147141546/e2b52731-044c-4331-8b13-e7a1f290535d)
```

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
