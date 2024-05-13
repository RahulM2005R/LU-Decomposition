# EX-5 :LU Decomposition 
## DATE: 30.03.2024
## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### Step1:
Define the package as scipy.linalg import lu.
### Step2:
Get input from user and print L and U matrix by 'print' .
### Step3:
Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
### Step4:
Print the variable 'X' 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Rahul M R
RegisterNumber: 2305003005
*/
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U = lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Rahul M R
RegisterNumber: 2305003005
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu,piv = lu_factor(A)
x= lu_solve((lu,piv),b)
print(x)
```

## Output:
![image](https://github.com/RahulM2005R/LU-Decomposition/assets/166299886/765377c7-9e1c-4efa-8515-7426562c1423)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

