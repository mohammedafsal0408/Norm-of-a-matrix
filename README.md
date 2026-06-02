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
Python
# Register No: 212225040247
# Developed By: MOHAMMED AFSAL S
# 1-Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
norm=np.linalg.norm(a,1)
print("{:.2f}".format(norm))


# 2-Norm of a Matrix

import numpy as np
A=np.array(eval(input()))
norm=np.linalg.norm(A,2)
print("{:.2f}".format(norm))


# Infinity Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
norm=np.linalg.norm(a,np.inf)
print("{:.2f}".format(norm))

```
## Output:
### 1-Norm of a Matrix
<img width="659" height="206" alt="image" src="https://github.com/user-attachments/assets/fde68056-13e1-4db4-a110-9e3a07900d96" />

### 2-Norm of a Matrix
<img width="722" height="242" alt="image" src="https://github.com/user-attachments/assets/6b2609c3-1cd5-4964-905e-3493f9fc93f2" />

### Infinity Norm of a Matrix
<img width="632" height="201" alt="image" src="https://github.com/user-attachments/assets/e8cf87fd-23d2-4bec-a08a-222a9edcc99a" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
