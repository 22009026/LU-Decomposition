# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy package
2. Import scipy.linalg package to solve LU decomposition
3. Get the input of the matrix
4. Print the result

## Program:
```python
(i) To find the L and U matrix

Program to find L and U matrix using LU decomposition.
Developed by: Lavanya M
RegisterNumber: 22009026

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)



(ii) To find the LU Decomposition of a matrix


Program to find the LU Decomposition of a matrix.
Developed by: Lavanya M
RegisterNumber: 22009026
import numpy as np
from scipy.linalg import lu_factor,lu_solve 
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)

```

## Output:
![](./lu%201.png)
![](./lu%20new.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.