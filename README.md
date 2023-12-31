# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
import numpy as np
### Step 2: 
define the matrix as A
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
print the result in output using print()function
## Program:
#Program to find the eigen values and eigen vectors.
#Developed by:Roshini.S
#RegisterNumber:23008859
import numpy as np
a=[[2,-3,0],[2,-5,0],[0,0,3]]
values,vectors=np.linalg.eig(a)
print("Eigen values are",values,"and Eigen Vectors are",vectors)

## Output:
![image](https://github.com/23008859/EIGENVALUES-AND-EIGENVECTORS/assets/139117979/f9637984-fedb-4ed8-a5fe-1a05c956ca72)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
