# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the buildin function for calculation
### Step 2:
prepare the list from each linear equation and assign in np.array().
### Step 3:
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
End the program
## Program:
```
#Program to find the rank of a matrix.
#Developed by: Farhana H
#RegisterNumber:23012987
import numpy as np
A=np.array([[3,2,5],[1,1,2],[3,3,6]])
rank = np.linalg.matrix_rank(A)
print(rank)
```
## Output:
![image](https://github.com/syedfayaz3105/RANK-OF-A-MATRIX/assets/147144126/5d832601-2c51-4e2f-a48d-de58ed709232)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

