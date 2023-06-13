# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :  import numpy as np
### Step 2: assign the values of the matrix to a variable using np.array
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:  print the eigen values and eigen vectors

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Jeyabalan
#RegisterNumber: 212222240040
import numpy as np
a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
x,y=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(x,y))
```

## Output:
![image](https://github.com/jeyaqbalan7/EIGENVALUES-AND-EIGENVECTORS/assets/119393851/9fdd8a71-812d-400e-aa55-9a115e897536)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
