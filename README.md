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
# Register No:212225040384
# Developed By: SARANYA R
# 1-Norm of a Matrix

import os
os.environ['OPENBLAS_NUM_THREADS']="1"
import numpy as np
A=np.array(eval(input()))
normal=np.linalg.norm(A,1)
print(normal)



# 2-Norm of a Matrix

import os
os.environ['OPENBLAS_NUM_THREADS']="1"
import numpy as np
A=np.array(eval(input()))
norm2=np.linalg.norm(A,2)
print(f"{norm2:.2f}")



# Infinity Norm of a Matrix

import os
os.environ['OPENBLAS_NUM_THREADS']="1"
import numpy as np
A=np.array(eval(input()))
norminf=np.linalg.norm(A,np.inf)
print(f"{norminf:.2f}")



```
## Output:
### 1-Norm of a Matrix
<img width="899" height="358" alt="image" src="https://github.com/user-attachments/assets/135b67f3-90bb-47d0-9538-16dc677802cb" />


### 2-Norm of a Matrix
<img width="774" height="409" alt="image" src="https://github.com/user-attachments/assets/43e7852c-bf8c-4629-86dd-d2cb01768af5" />

### Infinity Norm of a Matrix
<img width="762" height="343" alt="image" src="https://github.com/user-attachments/assets/a7c0a2a2-8e32-42a1-a1db-886e51ad8750" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
