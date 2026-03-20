# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner


## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by:AKASHINI V 
RegisterNumber:212225230009
*/
```
```
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: AKASHINI V
RegisterNumber: 212225230009
*/
```
```
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
X = lu_solve((lu , piv),b)
print(X)

```

## Output:
(i)
<img width="1224" height="574" alt="Screenshot 2026-03-20 203041" src="https://github.com/user-attachments/assets/f9ef0e23-29d4-4055-aba5-9d591e4ff22a" />

(ii)
<img width="1225" height="314" alt="Screenshot 2026-03-20 203054" src="https://github.com/user-attachments/assets/6755b586-f7a7-4361-b9d7-cb649609138d" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

