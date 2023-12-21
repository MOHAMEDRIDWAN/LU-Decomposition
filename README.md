# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. IMPORTING NUMPY MODULE AS NP 
2. IMPORTING LU FUNCTION FROM SCIPY.LINALG MODULE
3. INITIALIZIZING A MATRIX IN THE VARIABLE A
4. STORING UPPER TRIANGULAR MATRIX IN VARIABLE U, LOWER TRIANGULER MATRIX IN VARIABLE L

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: MOHAMED RIDWAN A
RegisterNumber:23003133
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U) 
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: MOHAMED RIDWAN A
RegisterNumber: 23003133
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
*/
```

## Output:
<img width="518" alt="image" src="https://github.com/MOHAMEDRIDWAN/LU-Decomposition/assets/146993368/0776e590-79b1-4a77-b559-880d06da4a7f">


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

