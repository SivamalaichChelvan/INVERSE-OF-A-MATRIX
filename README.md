# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import numpy modules as np
### Step 2: Define the matrix as numpy array.
### Step 3: Using the np.linalg.inv(), we can find the inverse of the given matrix.
### Step 4: Display the result using print() function

## Program:
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array([[2,1,1],[1,1,1],[1,-1,2]])
b=np.linalg.inv(a)
print(b)
```
## Output:
<img width="1913" height="977" alt="Screenshot 2026-05-20 204305" src="https://github.com/user-attachments/assets/b4941c1a-2b5c-49ce-bc99-8686faf1a851" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

