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
Developed by: PYNAM VINODH
RegisterNumber: 23004069
'''
from scipy.linalg import lu
import numpy as np
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: PYNAM VINODH
RegisterNumber: 23004069
'''

# To print X matrix (solution to the equations)
 
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr = eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)
```

## Output:
(i) To find the L and U matrix
 ![image](https://github.com/PYNAMVINODH/LU-Decomposition/assets/145742678/36ade966-d73d-4b1f-b844-9e93ae70214b)
 
 (ii) To find the LU Decomposition of a matrix
![image](https://github.com/PYNAMVINODH/LU-Decomposition/assets/145742678/af27e2c5-7401-4d20-80ef-d6123ea2efb0)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

