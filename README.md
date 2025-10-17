# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### Step 1: Start the program.

### Step 2: Import the required libraries — numpy as np and scipy.linalg for LU decomposition.

### Step 3: Create a square matrix using a NumPy array.

### Step 4: Use the function scipy.linalg.lu() to perform LU decomposition of the given matrix.

### Step 5: Display the matrices P, L, and U.

### Step 6: Stop the program

## Program:
(i) To find the L and U matrix
```
/*
'''Program to find L and U matrix using LU decomposition.
Developed by: Pharsheen rahuman M
RegisterNumber: 212224230193
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
'''Program to solve a matrix using LU decomposition.
Developed by: Pharsheen Rahuman M
RegisterNumber: 212224230193
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),B)
print(X)
/*
```

## Output:
![lu decomposition]()
<img width="1884" height="1072" alt="image" src="https://github.com/user-attachments/assets/45ff8ebc-1c77-45a6-9ef9-8591704d2240" />
<img width="1910" height="1085" alt="image" src="https://github.com/user-attachments/assets/45595d7a-0c3e-487a-aff8-83345746b7f0" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

