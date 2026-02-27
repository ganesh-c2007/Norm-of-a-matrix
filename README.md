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
# Register No:212225230071
# Developed By:GANESH.C
# 1-Norm of a Matrix
# 1-Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
OneNorm=np.linalg.norm(InputArray,1)
print(OneNorm)



# 2-Norm of a Matrix
# 2-Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
TwoNorm=np.linalg.norm(InputArray,2)
print(f"{TwoNorm:.2f}")




# Infinity Norm of a Matrix

import numpy as np
InputArray=np.array(eval(input()))
InfinityNorm=np.linalg.norm(InputArray,np.inf)
print(InfinityNorm)




```
## Output:
### 1-Norm of a Matrix
![CODE_page-0001](https://github.com/user-attachments/assets/a70f72cf-368c-42be-bef1-343d166fd3e9)


### 2-Norm of a Matrix
![CODE_page-0002](https://github.com/user-attachments/assets/7d07855f-6e6a-4dff-932c-0a73f39aa1a3)

### Infinity Norm of a Matrix
![CODE_page-0003](https://github.com/user-attachments/assets/796c7d7d-ef4e-4a92-b160-0f2c3f9f7d65)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
