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
## Expected output:
![image](https://github.com/user-attachments/assets/905bb4e0-7a3d-4c02-8af0-46998c86f0ec)
## Got:
![image](https://github.com/user-attachments/assets/bf85134d-aee7-4aaa-b7ef-455f88dbc3ab)



## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
