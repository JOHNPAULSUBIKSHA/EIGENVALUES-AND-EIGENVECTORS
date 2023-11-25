# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Strat the Program

### Step 2:
Difine your matrix and calcutate Eigen values and eigenvectors

### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4: 
End the Program

## Program:
#Program to find the eigen values and eigen vectors.
#Developed by: John Paul J
#RegisterNumber:23011778
import numpy as np
A=[[2,2],[1,3]]
values,vectors=np.linalg.eig(A)
print("Eigen values are",values,"and Eigen Vectors are",vectors)

## Output:
![output](/Eigenvalues.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
