# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the NumPy module to access linear algebra functions.
### Step 2: 
Define a square matrix using np.array().
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Display the eigenvalues and eigenvectors using print statements

## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by: abheek.a
#RegisterNumber:212224100001
import numpy as np
matrix = np.array([[2, -3, 0], 
                   [2, -5, 0], 
                   [0, 0, 3]])
eigenvalues, eigenvectors = np.linalg.eig(matrix)
print("Eigen values are", eigenvalues, "and Eigen Vectors are", eigenvectors)
```

## Output:
![Screenshot 2025-04-25 151944](https://github.com/user-attachments/assets/3dfc4ffa-8fde-4550-9288-347177baacc0)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
