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
#-Norm of a Matrix
```Python
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
InputArray=np.array(eval(input()))
OneNorm=np.linalg.norm(InputArray,1)
print(OneNorm)
```
# 2-Norm of a Matrix
```Python
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
InputArray=np.array(eval(input()))
TwoNorm=np.linalg.norm(InputArray,2)
print(f"{TwoNorm:.2f}")
```
# Infinity Norm of a Matrix
```Python
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
InputArray=np.array(eval(input()))
InfinityNorm=np.linalg.norm(InputArray,np.inf)
print(InfinityNorm)
```
## Output:
###1-Norm of a Matrix

<img width="1204" height="787" alt="Screenshot 2026-05-17 142351" src="https://github.com/user-attachments/assets/23d52776-c4eb-4ea9-b36e-dbfe8422fe33" />


### 2-Norm of a Matrix
<img width="1302" height="857" alt="Screenshot 2026-05-21 135545" src="https://github.com/user-attachments/assets/d121c38c-916c-46a1-8d0e-72820ab10a0f" />




### 3-Infinity Norm of a Matrix

<img width="1347" height="860" alt="Screenshot 2026-05-17 142420" src="https://github.com/user-attachments/assets/15b8f5d3-310b-4870-9bca-02ded6b5fdda" />


## Result:
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.

