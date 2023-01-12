# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. to find L and U matrix using LU decomposition.
2. import numpy as np
3. from scipy.linalg import lu
4. Print(L) & Print(U)

## Program:
(i) To find the L and U matrix
```
Program to find L and U matrix using LU decomposition.
Developed by:R.Vignesh
RegisterNumber:22008489

import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
## Output:
![](/LU%20Decomposition2.png)

(ii) To find the LU Decomposition of a matrix
```
Program to solve a matrix using LU decomposition.
Developed by:R.Vignesh 
RegisterNumber:22008489

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu, piv =lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)
```
## Output:
![](/LU%20Decomposition.png)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

