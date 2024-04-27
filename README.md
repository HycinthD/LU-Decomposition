# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Write the code
2. Get input for a,b
3. Rn built in function eval
4. Run the code

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: HYCINTH D
RegisterNumber: 21223240055
*/
```
```
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: HYCINTH D
RegisterNumber: 
*/212223240055
```
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
l,p=lu_factor(a)
x=lu_solve((l,p),b)
print(x)
```

## Output:
![lu decomposition]()
1)
![alt text](<Screenshot (203).png>)
2)
![alt text](<Screenshot (204).png>)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

