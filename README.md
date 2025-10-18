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
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: G.Sindhu Priya Reddy
RegisterNumber: 212224040319
'''
import numpy as np
from scipy .linalg import lu
matrix=np.array(eval(input()))
P,L,U=lu(matrix)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.

'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pv=lu_factor(A)
result= lu_solve((lu,pv),B)
print(result)
```

## Output:
(i) To find the L and U matrix

<img width="1206" height="896" alt="Screenshot 2025-09-29 144250" src="https://github.com/user-attachments/assets/1da9b3a1-df3d-4bc9-909b-59385cdf5280" />


(ii) To find the LU Decomposition of a matrix

<img width="1185" height="746" alt="Screenshot 2025-09-29 144342" src="https://github.com/user-attachments/assets/ed6f24d1-7cc2-41ef-b103-3321fc5e271a" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

