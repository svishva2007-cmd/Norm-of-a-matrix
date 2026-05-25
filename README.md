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
Developed by: vishvabala
RegisterNumber: 212225040496
# 1-Norm of a Matrix
"""program to find the 1-Norm of a matrix
Development by : Vishvabala
Register no :212225040496 """
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
Inputarray=np.array(eval(input()))
OneNorm=np.linalg.norm(Inputarray,1)
print(OneNorm)



# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: vishvabala
RegisterNumber: 212225040496
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
InputArray=np.array(eval(input()))
TwoNorm=np.linalg.norm(InputArray,2)
print(f"{TwoNorm:.2f}")


# Infinity Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: vishvabala
RegisterNumber: 212225040496
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
InputArray=np.array(eval(input()))
InfinityNorm=np.linalg.norm(InputArray,np.inf)
print(f"{InfinityNorm:.2f}")



```
## Output:
### 1-Norm of a Matrix
<img width="1191" height="359" alt="image" src="https://github.com/user-attachments/assets/47fbf85c-dbc0-4a0a-83f7-42560c0d36ed" />
<img width="1234" height="221" alt="image" src="https://github.com/user-attachments/assets/e5ea011a-aed9-4edd-9eac-cfb9edcc7a4e" />


### 2-Norm of a Matrix
<img width="1183" height="302" alt="image" src="https://github.com/user-attachments/assets/f1f9aff8-bbcb-47f6-a3e6-ec85e7e8c72f" />
<img width="1240" height="273" alt="image" src="https://github.com/user-attachments/assets/ed94858b-311b-4e1b-9ac4-ab69eb5234da" />


### Infinity Norm of a Matrix
<img width="1210" height="410" alt="image" src="https://github.com/user-attachments/assets/3676daf6-5c06-479e-aca5-63f312c9e033" />
<img width="1221" height="325" alt="image" src="https://github.com/user-attachments/assets/f347b5cd-3f30-4890-b0d0-5d5990d3c239" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
