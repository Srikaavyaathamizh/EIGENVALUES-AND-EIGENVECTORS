# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import numpy aas np
### Step 2: Define the matrix 'a'
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the eigenvalues and eigenvectors

## Program:`
```
#Program to find the eigen values and eigen vectors.
#Developed by: SRIKAAVYAA T
#RegisterNumber:23013589
import numpy as np
a=[[2,-3,0],[2,-5,0],[0,0,3]]
values,vectors=np.linalg.eig(a) 
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
![Alt text](<Screenshot 2023-12-17 003934.png>)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
