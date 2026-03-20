# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program
2. Import the necessary libraries(numpy,scipy.linalg)
3. Define the matrix using numpy
4. Use lu(),lu_solve(),lu_factor() to get the solutions
5. End the program 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Aditya Jorim F S
RegisterNumber: 212225240004
*/
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Aditya Jorim F S
RegisterNumber: 212225240004
*/
# To print X matrix (solution to the equations)

import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
X = lu_solve((lu , piv),b)
print(X)

```

## Output:
<img width="1158" height="747" alt="Screenshot 2026-03-20 152525" src="https://github.com/user-attachments/assets/6e7e6d53-7680-4dab-9979-7bce5eec3f75" />
<img width="1097" height="639" alt="Screenshot 2026-03-20 153353" src="https://github.com/user-attachments/assets/9a4f35df-0a8d-4f40-b7d3-a9177955feae" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

