# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
Define the package as scipy.linalg import lu.

2.Get input from user and print L and U matrix by 'print'.

3.Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.

4.print the variable 'X'



## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: S VASUNTHARA SAI
RegisterNumber: 212224230297
*/
import numpy as np
from scipy.linalg import lu
a=eval(input())
P,L,U=lu(a)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: S VASUNTHARA SAI
RegisterNumber: 212224230297
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu, piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)

```

## Output:
![Screenshot 2025-03-24 084332](https://github.com/user-attachments/assets/cefdc908-067d-4db7-bca9-f3c76a83f5ec)
![Screenshot 2025-03-24 084340](https://github.com/user-attachments/assets/8f64bd8f-8669-4db8-964f-be0fd812a493)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

