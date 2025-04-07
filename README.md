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
Using the np.linalg.matrix_rank(), we can find the inverse of the given matrix
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
![{983E0C8D-3F99-408E-8331-83F10541AB0F}](https://github.com/user-attachments/assets/20b68fa7-d01d-4394-b136-9015fa6970de)

## Result:
Thus the inverse of given matrix is successfully solved using python program

