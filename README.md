# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import os and numpy libray
### Step 2: define the sq matrix A using numpy.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: print the result

## Program:import os  

os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy

A=numpy.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])

values,Vectors=numpy.linalg.eig(A)

print("Eigen values are {} and Eigen Vectors are {}".format(values,Vectors))

## Output:<img width="1227" height="774" alt="{39D0534C-83FE-47EC-B10C-96E441972A55}" src="https://github.com/user-attachments/assets/5cd8a1f5-eba1-48fa-a4f6-fae95b3f5584" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
