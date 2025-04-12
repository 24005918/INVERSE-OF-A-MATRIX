# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each equations and assign in np.array()
### Step 3: 
Use the np.linalg.inv()
### Step 4: 
End the program

## Program:
#Program to find the inverse of a matrix.

#Developed by: SANTHOSH V

#RegisterNumber: 212224230252

import numpy as np

A = np.array([[6, 2, 3],
              [3, 1, 1],
              [10, 3, 4]])
try:

    A_inv = np.linalg.inv(A)
    
    print(A_inv)
    
except np.linalg.LinAlgError:

    print("Matrix is singular and cannot be inverted.")

## Output:
![{881F37D0-ABF9-4293-9DB7-E0FA5C86BBDA}](https://github.com/user-attachments/assets/120dd00d-5ec4-4be9-a6c1-4d3d978a579e)

## Result:
Thus the inverse of given matrix is successfully solved using python program

