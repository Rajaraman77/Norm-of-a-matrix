# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No:23014299
# Developed By:RAJARAMAN V
# 1-Norm of a Matrix
#Program to find 1-norm of a matrix.
#Developed by: RAJARAMAN V
#RegisterNumber: 23014299
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by:RAJARAMAN V
RegisterNumber: 23014299
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
# Infinity Norm of a Matrix
'''
Program to find the infinity of a matrix.
Developed by:RAJARAMAN V
RegisterNumber: 23014299
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/Rajaraman77/Norm-of-a-matrix/assets/150319383/16688764-efb0-4464-8643-6a79498f9431)
### 2-Norm of a Matrix
![image](https://github.com/Rajaraman77/Norm-of-a-matrix/assets/150319383/a3994ada-2d51-4353-ac86-4c626fde4704)
### Infinity Norm of a Matrix
![image](https://github.com/Rajaraman77/Norm-of-a-matrix/assets/150319383/47503313-2ec4-48f2-a240-c915c44e6eeb)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
