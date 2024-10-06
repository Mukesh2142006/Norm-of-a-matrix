# DATE:
# EXP NO: 7
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
# Register No:MUKESH.B
# Developed By:212223230128
# 1-Norm of a Matrix


import numpy as np
mat=np.array (eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)




# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: MUKESH.B
RegisterNumber: 212223230128
'''
import numpy as np
mat=np.array (eval (input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)





# Infinity Norm of a Matrix


#Developed by:MUKESH.B
#Reg no:212223230128
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print (Norm_of_matrix)


```
## Output:
### 1-Norm of a Matrix

![Screenshot 2024-10-06 230613](https://github.com/user-attachments/assets/ae7a3df1-f876-4834-8f56-fd05a87bdca0)


### 2-Norm of a Matrix
![Screenshot 2024-10-06 230623](https://github.com/user-attachments/assets/c23ceaae-7d78-4445-b289-a7ba3bb45133)


### Infinity Norm of a Matrix

![Screenshot 2024-10-06 230631](https://github.com/user-attachments/assets/d3b2b1d5-5be3-4a08-9d7e-f208759bde1b)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
