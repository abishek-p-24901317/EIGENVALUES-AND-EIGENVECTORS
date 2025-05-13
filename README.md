# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
: Import the NumPy library and define a square matrix A.
### Step 2: 
Use the np.linalg.eig() function to compute the eigenvalues and eigenvectors of matrix A.
### Step 3: 
Store the eigenvalues in the variable values.
These represent the characteristic roots of the matrix.
### Step 4: 
Store the eigenvectors in the variable vectors.
Each column in vectors corresponds to an eigenvector of the matrix.
### step 5:
Display the eigenvalues and eigenvectors using the print() function.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: ABishek P
#RegisterNumber: 24901317
import numpy as np
a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {}'.format(values,vectors))
```

## Output:
![image](https://github.com/user-attachments/assets/5cce0740-ce6e-4c0a-b3bb-b5ce580626fb)
![image](https://github.com/user-attachments/assets/cad222e0-57f3-4207-be50-9b8d7bd81f19)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
