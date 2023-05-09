# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### Step 1:
Import numpy library using import statement.

### Step 2:
From scipy package import lu_factor() and lu_solve().

### Step 3:
Get two inputs from user and pass it as matrix array.

### Step 4:
Find lu and pivot value of first matrix using lu_factor().

### Step 5:
Find solution of the matrix by using lu_solve() by passing lu, pivot values as first argument and second matrix as second argument.

### Step 6:
Print the solution.

 

## Program:
(i) To find the L and U matrix
```
Program to find L and U matrix using LU decomposition.
Developed by:Matheswaran k
RegisterNumber:212222110024

import numpy as np
from scipy.linalg import lu
arr=np.array(eval(input()))
P,L,U=lu(arr)
print(L)
print(U)
```
```
(ii) To find the LU Decomposition of a matrix
Program to solve a matrix using LU decomposition.
Developed by: Matheswaran k
RegisterNumber: 212222110024

import numpy as np
from scipy.linalg import lu_factor,lu_solve
arr=np.array([[3, 2, 7], [2, 3, 1], [3, 4, 1]])
B=np.array([4, 5, 7])
LU,P=lu_factor(arr)
res=lu_solve((LU,P),B)
print(res)
```

## Output:
   -  ## LU Decomposition to find L and U matrix
![p1](https://user-images.githubusercontent.com/119477782/237006589-773f0501-7912-4460-a873-a66d0770c1e7.png)
  -  ## LU Decomposition to solve a matrix
![p1 1](https://user-images.githubusercontent.com/119477782/237007438-951d1483-0aeb-46d9-b09a-ba11957d459a.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

