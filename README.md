# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
```
step1:Define the package as scipy.linalg import lu.
step2:Get input from user and print L and U matrix by 'print' .
step3:Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
step4:print the variable 'X'
```    

## Program:
(i) To find the L and U matrix
```
Program to find the L and U matrix.
Developed by: NARENDHARAN.M
RegisterNumber: 212223230134
```
```
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U,=lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by: NARENDHARAN.M
RegisterNumber: 212223230134
```
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),b)
print(X)

```

## Output:

![image](https://github.com/user-attachments/assets/8b35bad3-85ca-43b1-a9bb-0d9d50e82b42)
```
```
![image](https://github.com/user-attachments/assets/82d4bce7-ccb2-4d55-8fa0-528eb7c13015)
```










 


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

