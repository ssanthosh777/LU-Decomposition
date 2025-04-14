# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' . 
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable
4. print the variable 'X'

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: SANTHOSH S
RegisterNumber: 212224100052
'''
from scipy.linalg import lu
a=eval(input())
p,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: SANTHOSH S
RegisterNumber: 212224100052
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor, lu_solve
a=eval(input())
b=eval(input())
lu,plv=lu_factor(a)
x=lu_factor(a)
x=lu_solve((lu,plv),b)
print(x)
```

## Output:
(i) To find the L and U matrix
![Screenshot (147)](https://github.com/user-attachments/assets/f272b512-6e7f-4da6-a571-3a12b6abf0ea)

(ii) To find the LU Decomposition of a matrix
![Screenshot (148)](https://github.com/user-attachments/assets/f2e792bd-3845-4026-ab3b-872940793db1)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

