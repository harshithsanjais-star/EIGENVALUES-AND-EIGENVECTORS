# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
### Step 2: 
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 

## Program:
#Program to find the eigen values and eigen vectors.
#Developed by: Mahith M
#RegisterNumber:212225220061
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A = np.array([[2, 2],
              [1, 3]])

eigenvalues, eigenvectors = np.linalg.eig(A)

print("Eigen values are", eigenvalues,"and Eigen Vectors are", eigenvectors)

## Output:
<img width="1866" height="872" alt="image" src="https://github.com/user-attachments/assets/fe877aa2-b3d6-481d-9648-55a5a3da7bb7" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
