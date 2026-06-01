# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program 
2. Import the necessary libraries(numpy,scipy.linalg)
3. Define the matrix using numpy 
4. Use lu(),lu_solve(),lu_factor() to get the solutions
5. End the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: yukesh s
RegisterNumber: 212225100062
*/
import numpy as np
from scipy.linalg import lu
Inputmatrix=np.array(eval(input()),dtype='i')
piv,Lmatrix,Umatrix=lu(Inputmatrix)
print(Lmatrix)
print(Umatrix)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: yukesh s
RegisterNumber: 212225100062
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
amatrix=np.array(eval(input()),dtype='i')
bmatrix=np.array(eval(input()),dtype='i')
xmatrix=lu_factor(amatrix)
solution=lu_solve(xmatrix,bmatrix)
```

## Output:

<img width="1291" height="538" alt="image" src="https://github.com/user-attachments/assets/b09d568e-ab70-4b4e-8149-a2068e930a4d" />
<img width="1291" height="538" alt="image" src="https://github.com/user-attachments/assets/61ebfd08-50ef-44a2-a543-aa86616ebef9" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

