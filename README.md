# LU Decomposition without zero on the diagonal

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
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Ranjith D
RegisterNumber: 21500662
*/
```
~~~
import numpy as np
from scipy.linalg import lu
x=eval(input())
A=np.array(x)
P,L,U=lu(A)
print(L)
print(U)
~~~
~~~
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array([[3, 2, 7], [2, 3, 1], [3, 4, 1]])
B=np.array([4, 5, 7])
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
~~~
## Output:
![lu decomposition](https://github.com/RanjithD18/LU-Decomposition/blob/main/Screenshot%20from%202021-12-20%2010-37-18.png?raw=true)
![lu decomposition](https://github.com/RanjithD18/LU-Decomposition/blob/main/Screenshot%20from%202021-12-20%2010-37-28.png?raw=true)
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

