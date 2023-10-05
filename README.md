# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### 1. import numpy as np
### 2. from scipy.linalg import lu,lu_factor,lu_piv
### 3. Get input from the user as eval(input())
### 4. Use lu_factor and lu_solve to find LU decomposition
### 5. print L,U
### 6. print x
## Program:
(i) To find the L and U matrix
```Program to find L and U matrix using LU decomposition.
Developed by: DEEPAK RAJ S
RegisterNumber: 212222240023
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
'''Program to solve a matrix using LU decomposition.
Developed by: DEEPAK RAJ S
RegisterNumber: 212222240023
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),B)
print(X)

*/
```

## Output:
![image](https://github.com/DEEPAK2200233/LU-Decomposition/assets/118707676/74927b5a-3118-405c-aded-cb039a87be81)

![image](https://github.com/DEEPAK2200233/LU-Decomposition/assets/118707676/a75d4175-54ed-477a-9cd3-b4cb7a42f85d)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

