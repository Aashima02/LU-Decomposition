# 5 a) LU Decomposition without zero on the diagonal

## AIM:
To write a program to find the LU Decomposition of a matrix.

## EQUIPMENTS REQUIRED:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## ALGORITHM:
### Step 1:
Import numpy library using import statement.

### Step 2:
From scipy package import lu().

### Step 3:
Get input from user and pass it as an array.

### Step 4:
Get P, L, U matrix using lu()

### Step 5:
Print L and U matrix

## PROGRAM:
```
Program to find L and U matrix using LU decomposition.
Developed by: Aashima Nazreen Sayeed S
RegisterNumber: 21500368
# To print L and U matrix

import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P, L, U = lu(A)
print(L)
print(U)
```


## OUTPUT:
!![outputa](https://user-images.githubusercontent.com/93427086/147100547-ec28a78f-3a9d-4b8e-9619-2e91a33b942e.png)



## RESULT:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.




# 5 b) LU Decomposition without zero on the diagonal

## AIM:
To write a program to find the LU Decomposition of a matrix.

## EQUIPMENTS REQUIRED:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## ALGORITHM:
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

## PROGRAM:
```
Program to solve a matrix using LU decomposition.
Developed by: Aashima Nazreen Sayeed S
RegisterNumber: 21500368
# To print X matrix (solution to the equations)

import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
B = np.array(eval(input()))
lu, pivot = lu_factor(A)
x = lu_solve((lu,pivot),B)
print(x)
```


## OUTPUT:
![outputb](https://user-images.githubusercontent.com/93427086/147100590-1fb97dbd-f945-4495-81a4-78c8f9ddf799.png)


## RESULT:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

