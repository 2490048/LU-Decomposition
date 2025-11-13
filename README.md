# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Take matrix input from the user and convert it to a NumPy array.
2.Apply LU decomposition using scipy.linalg.lu() to get P, L, and U.

3.Extract the L (lower) and U (upper) triangular matrices.

4.Print the L and U matrices 

## Program:
Name : Rahul RP
Reg num : 212224240125
(i) To find the L and U matrix
```
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U = lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b=np.array(eval(input()))
lu, piv = lu_factor(A)
x = lu_solve((lu , piv),b)
print(x)
```

## Output:
(i) To find the L and U matrix

<img width="1713" height="813" alt="image" src="https://github.com/user-attachments/assets/d6760a75-22fb-4019-bfee-e0c1710972c1" />



(ii) To find the LU Decomposition of a matrix

<img width="1716" height="472" alt="image" src="https://github.com/user-attachments/assets/bd82ca18-2b30-4135-ac8b-a850cf897256" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

