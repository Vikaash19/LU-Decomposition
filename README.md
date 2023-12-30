# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### Algorithm for L and U Matrix
1. Import the numpy module to use the built-in functions for calculation
2. from scipy.linalg import lu
3. Enter the lists from each linear equations and assign in np.array()
4. using lu() and store it in three variables
5. print the L and U Matrix
6. End the program
### Algorithm for LU Decomposition
1. Import the numpy module to use the built-in functions for calculation
2. from scipy.linalg import lu_factor,lu_solve
3. Enter the lists from each linear equations and assign in np.array()
4. Enter the lists from each linear equations and assign in np.array()
5. using lu_factor() and store it in two variables
6. using lu_solve(),we can find L and U matrix
7. End the program
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

