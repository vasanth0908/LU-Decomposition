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
/*
'''Program to find L and U matrix using LU decomposition.
Developed by: vasanth.s 
RegisterNumber: 212222110052
'''
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
<img width="574" alt="13" src="https://github.com/vasanth0908/LU-Decomposition/assets/122000018/19773471-60a3-4117-adef-d0fe9d975f68">

```
/*
'''Program to solve a matrix using LU decomposition.
Developed by: vasanth.s
RegisterNumber: 212222110052
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = eval(input())
B = eval(input())
lu,piv = lu_factor(A)
x = lu_solve((lu,piv),B)
print(x)

*/
```

## Output:
<img width="502" alt="14" src="https://github.com/vasanth0908/LU-Decomposition/assets/122000018/ac673cad-d28f-4c19-9b1a-156f08873d13">


![lu decomposition]()


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

