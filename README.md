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
# Register No:212225230083
# Developed By:GOPIKA DHARSHINI.N
# 1-Norm of a Matrix
```
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
InputArray=np.array(eval(input()))
OneNorm=np.linalg.norm(InputArray,1)
print(OneNorm)
```



# 2-Norm of a Matrix
```
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
InputArray=np.array(eval(input()))
TwoNorm=np.linalg.norm(InputArray,2)
print(f"{TwoNorm:.2f}")
```



# Infinity Norm of a Matrix
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
InputArray=np.array(eval(input()))
InfinityNorm=np.linalg.norm(InputArray,np.inf)
print(InfinityNorm)
```

```
## Output:
### 1-Norm of a Matrix
<img width="1490" height="879" alt="Screenshot 2026-05-21 135525" src="https://github.com/user-attachments/assets/2bf67dfe-20e3-426b-9a27-b2b015bef379" />


### 2-Norm of a Matrix
<img width="1379" height="839" alt="Screenshot 2026-05-21 135602" src="https://github.com/user-attachments/assets/81b65c97-fb98-4b27-b452-5eb57e8dec7a" />


### Infinity Norm of a Matrix
<img width="1490" height="879" alt="Screenshot 2026-05-21 135525" src="https://github.com/user-attachments/assets/5114c2bf-82d3-4875-9bb4-c6d91704c83e" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
