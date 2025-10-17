# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: LOGESH B
#RegisterNumber: 21222110034
import numpy as np
a = np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors = np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
<img width="1290" height="926" alt="image" src="https://github.com/user-attachments/assets/3d267616-d1a8-4c21-8c39-d031e810b07b" />
<img width="1285" height="285" alt="image" src="https://github.com/user-attachments/assets/66e80631-2021-4610-a8d3-fa61a17da17f" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
