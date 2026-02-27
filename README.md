# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
```
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
```
## Program:
```Python
# Register No:212225230071
# Developed By:GANESH.C
# 1-Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
OneNorm=np.linalg.norm(InputArray,1)
print(OneNorm)



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
<img width="1221" height="427" alt="Screenshot 2026-02-27 214823" src="https://github.com/user-attachments/assets/dda47ed4-c723-43e1-99e9-d0dfbccf0494" />


### 2-Norm of a Matrix
<img width="1175" height="620" alt="Screenshot 2026-02-27 214914" src="https://github.com/user-attachments/assets/63f473d5-f767-48be-b907-d0358f313c1d" />


### 3-Infinity Norm of a Matrix
<img width="1204" height="365" alt="Screenshot 2026-02-27 215017" src="https://github.com/user-attachments/assets/e8027a15-9507-4692-bf5e-21bfee3b815d" />



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
