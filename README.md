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
Developed by: Sowmiya G
RegisterNumber: 2305002023
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
Developed by: Sowmiya G
RegisterNumber: 2305002023
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
![image](https://github.com/RahulM2005R/LU-Decomposition/assets/166299886/6b248fb3-6595-4a70-8565-b676f87f1c5a)
![image](https://github.com/RahulM2005R/LU-Decomposition/assets/166299886/05cb895e-87b1-4dd4-9322-9f3d9f59595d)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

