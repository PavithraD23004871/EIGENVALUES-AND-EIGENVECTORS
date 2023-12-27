# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
# Step1 :
Import the numpy module to use the built-in functions for calculation

# Step 2:
Prepare the lists from each eigenvalues,eigenvectors and assign in np.array()

# Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

# Step 4:
End the program

## Program:
``````
#Program to find the eigen values and eigen vectors.
#Developed by: PAVITHRA.D
#RegisterNumber:23004871
import numpy as np
A=[[-2,2,-3],[2,1,-6],[-1,-2,0]]
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
``````
## Output:
![maths ex4](https://github.com/PavithraD23004871/EIGENVALUES-AND-EIGENVECTORS/assets/138955967/c74a96b1-3d15-42c9-832f-15094835bc74)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
