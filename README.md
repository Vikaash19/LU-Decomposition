# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: Vikaash K S
RegisterNumber: 23013426
'''
import numpy as n
from scipy.linalg import lu
a=n.array(eval(input()))
P,L,U=lu(a)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: Vikaash K S
RegisterNumber: 23013426
'''
# To print X matrix (solution to the equations)
import numpy as n
from scipy.linalg import lu_factor,lu_solve
a=n.array(eval(input()))
b=n.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```
## Output:
(i) To find the L and U matrix
![LU decomposition](https://github.com/Vikaash19/LU-Decomposition/assets/148514589/cf4a1c3c-bd91-4f60-aad5-a66dd0069d32)

(ii) To find the LU Decomposition of a matrix
![LU solve](https://github.com/Vikaash19/LU-Decomposition/assets/148514589/0d2e9117-6c3b-496f-b989-d24c757668aa)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

