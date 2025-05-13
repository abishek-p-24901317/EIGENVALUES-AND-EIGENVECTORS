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
```#Program to find the eigen values and eigen vectors.
#Developed by: ABishek P
#RegisterNumber: 24901317
import numpy as np
a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {}'.format(values,vectors))```

## Output:
![WhatsApp Image 2025-05-13 at 19 52 37_5c67d1e7](https://github.com/user-attachments/assets/32dc5b8a-37da-440d-9158-99b333f737d8)
![WhatsApp Image 2025-05-13 at 19 52 38_7a8b17e5](https://github.com/user-attachments/assets/7c420f75-3ac9-4218-bc85-565628fcb219)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
