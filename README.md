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
```
#Program to find the eigen values and eigen vectors.
#Developed by: Murali Krishna S
#RegisterNumber:212223230129
import numpy as np
A=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:
![image](https://github.com/Murali-Krishna0/EIGENVALUES-AND-EIGENVECTORS/assets/149054535/e656fc26-cf14-4927-a2f2-4f754e08f7d5)
![image](https://github.com/Murali-Krishna0/EIGENVALUES-AND-EIGENVECTORS/assets/149054535/d0246465-c328-4ba5-a1db-391a62670137)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
