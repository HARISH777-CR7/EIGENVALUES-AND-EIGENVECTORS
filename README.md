# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : first import numpy using import numpy as np
### Step 2: create a array with values 
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: print the values and vectors using print()

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: HARISH K
#RegisterNumber:25013390
import numpy as np
a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(a)
print(f"Eigen values are {values} and Eigen Vectors are {vectors}")
```

## Output:
<img width="1919" height="1086" alt="Screenshot 2025-11-19 113715" src="https://github.com/user-attachments/assets/bbd2daa5-7202-470c-9557-58b49c706c5b" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
