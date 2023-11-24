# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import numpy as np
### Step 2: 
Initilize a variable 'a' as an array from thr np module
### Step 3:
 Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Now print the value.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Sasinthar.P
#RegisterNumber:23012532
import numpy as np
a=[[4,2],[2,4]]
Values,Vectors=np.linalg.eig(a)
print("Eigen values are",Values,"and Eigen Vectors are",Vectors)

```

## Output:
![Alt text](<Screenshot 2023-11-24 194811.png>)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
