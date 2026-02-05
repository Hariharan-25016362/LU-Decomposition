# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Start the program
2.Import the necessary libraries(numpy,scipy.linalg)
3.Define the matrix using numpy
4.Use lu(),lu_solve(),lu_factor() to get the solutions
5.End the program 

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: HARIHARAN M 
RegisterNumber: 212225240045 
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
/*
Program to find the L and U matrix.
Developed by: HARIHARAN M
RegisterNumber: 212225240045 
*/
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: HARIHARAN M
RegisterNumber: 212225240045
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)
/*
Program to find the LU Decomposition of a matrix.
Developed by:HARIHARAN M 
RegisterNumber: 212225240045 
*/
```

## Output:
<img width="1221" height="507" alt="Screenshot 2026-02-05 143223" src="https://github.com/user-attachments/assets/2c34b04e-b291-472e-9167-c664e42e698b" />
<img width="1233" height="324" alt="Screenshot 2026-02-05 143428" src="https://github.com/user-attachments/assets/be6e2378-0566-4248-8381-aa7b61e36e09" />





## Result:

Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

