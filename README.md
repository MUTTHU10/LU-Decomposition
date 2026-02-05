# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Write the python code for the given matrix.
2. import numpy library.
3. write the required code to perform the necessary operation.
4. Run the code and get the output.

## Program:
(i) To find the L and U matrix
```
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)
```

## Output:

<img width="1227" height="567" alt="image" src="https://github.com/user-attachments/assets/2e0c84a2-fe83-46ac-a2cc-5df5513856f9" />


<img width="983" height="332" alt="image" src="https://github.com/user-attachments/assets/3c5d910a-609d-4657-85ab-c8b5f6df15a0" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

