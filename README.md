# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import the numpy as np
2. from scipy.linalg import lu
3. enter the lists from each linear equationa and assgin in np.array()
4. using lu( )and store it in three variables
5. print the L and U matrix
6. end the program

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: guntur shaik mohammad shahil
RegisterNumber: 23011002
'''
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
P,L,U=lu(a)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: guntur shaik mohammad shahil
RegisterNumber: 23011002
'''
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
## i)
![image](https://github.com/mohammadshahil09/LU-Decomposition/assets/145742840/83492613-3fba-45c5-94a6-2b0a87f1d550)

## ii)
![image](https://github.com/mohammadshahil09/LU-Decomposition/assets/145742840/e3de9025-bdca-4556-b8f5-dec509d138a0)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.
