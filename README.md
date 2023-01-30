# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy library as np
2. Create a matrix using np.array()
3. Using scipy.linalg.lu() find L and U, also using scipy.linalg.lu_solve() get the result for LU Decomposition
4. Get the output and end the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
#Developed by: Rakesh.V
#RegisterNumber: 22008590

import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P, L, U = lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
#Developed by: Rakesh.V
#RegisterNumber: 22008590

import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
x = lu_solve((lu, piv), b)
print(x)
*/
```

## Output:
![lu decomposition](./Screenshot%20from%202023-01-30%2014-06-30.png)
![lu decomposition](./Screenshot%20from%202023-01-30%2014-06-40.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

