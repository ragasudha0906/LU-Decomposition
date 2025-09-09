# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. print the variable 'X

## Program:
(i) To find the L and U matrix
```
Program to find L and U matrix using LU decomposition.
Developed by:RAGASUDHA R 
RegisterNumber: 212224230215
import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
P,L,U=lu(matrix)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Program to solve a matrix using LU decomposition.
Developed by: RAGASUDHA R
RegisterNumber: 212224230215
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
result=lu_solve((lu,pivot),B)
print(result)
```

## Output:


<img width="1226" height="992" alt="python 5(b)" src="https://github.com/user-attachments/assets/50dc5e24-a4b3-4b91-8c20-69bd1f966f22" />
<img width="1249" height="936" alt="python 5(a)" src="https://github.com/user-attachments/assets/bb15ee71-8d79-4395-a3c8-b1d8fcc5642f" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

