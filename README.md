# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy as np
2. from scipy package import lu
3. get input from the user
4. print result

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: 
RegisterNumber:
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
P,L,U=lu(a)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: 
RegisterNumber:
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
l,p=lu_factor(a)
x=lu_solve((l,p),b)
print(x)
*/
```

## Output:
![lu decomposition]()
![Screenshot 2025-04-16 135430](https://github.com/user-attachments/assets/a6649e8e-d2cc-4853-9f7d-c2ec7be79095)
![Screenshot 2025-04-16 135452](https://github.com/user-attachments/assets/ad8e1c45-c3a7-4637-b94f-56455a354d65)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

