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
![{58D27055-E871-4734-BC06-822F21BC9A57}](https://github.com/user-attachments/assets/eda25034-0991-4c9b-9841-4aa24b00e69f)

## Result:
Thus the inverse of given matrix is successfully solved using python program

