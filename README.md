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
```
# 1-Norm of a Matrix
"""
program to find 2-norm of a matrix
Developed by: M ALMAAS JAHAAN
Register number:212224230016
"""
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm="{:.2f}".format(ans)
print(norm)


# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: M ALMAAS JAHAAN
RegisterNumber: 212224230016
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm="{:.2f}".format(ans)
print(norm)



# Infinity Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: M ALMAAS JAHAAN
RegisterNumber: 212224230016
'''
import numpy as np
mat=np.array(eval(input()))
norm=np.linalg.norm(mat,ord=np.inf)
print("{:.2f}".format(norm))




```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/user-attachments/assets/5f8c9a7c-e501-4e58-b0a9-e7b3d1d70ded)


### 2-Norm of a Matrix
![image](https://github.com/user-attachments/assets/05f95b11-782b-47c8-9d8d-e043dd887edd)


### Infinity Norm of a Matrix
![image](https://github.com/user-attachments/assets/4faf9ce5-8ee3-44bc-8acb-b5fc64b11cfe)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
