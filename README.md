# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. ## Algorithm 1  
1. Define the package as scipy.linalg import lu. 
2. Get input from user and print L and U matrix by 'print'
3. Define a package as "from scipy.linalg import lu_factor,lu_solve" and create the variable as 'X' include the package in that variable
4. print the variable 'X'

## Algorithm 2
1. Define the package as scipy.linalg import lu. 
2. Get input from user and print L and U matrix by 'print'
3. Define a package as "from scipy.linalg import lu_factor,lu_solve" and create the variable as 'X' include the package in that variable
4. print the variable 'X'
   
## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: CLARISSA K
RegisterNumber: 24009830
*/
```
'''Program to find L and U matrix using LU decomposition.
Developed by: clarissa k
RegisterNumber: 24009830
'''
import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
piv,l_matrix,u_matrix=lu(matrix)
print(l_matrix)
print(u_matrix)

(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: CLARISSA K
RegisterNumber: 24009830
*/
```
'''Program to solve a matrix using LU decomposition.
Developed by: clarissa k
RegisterNumber: 24009830
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
matrix=np.array(eval(input()))
b=np.array(eval(input()))
x=lu_factor(matrix)
solution=lu_solve(x,b)
print(solution)


## Output:
![lu decomposition]()



![Screenshot from 2024-12-26 10-42-20](https://github.com/user-attachments/assets/fb7bc1c8-33e7-4bf8-ab5f-18fb584c9268)




![Screenshot from 2024-12-26 11-54-26](https://github.com/user-attachments/assets/8b9ad008-b9c7-4711-b025-c08ff2779b1c)







## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

