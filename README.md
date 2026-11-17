# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### 1. Get the input matrix using np.array()   
### 2. Find the 2-norm of the matrix using np.linalg.norm()
### 3. Print the norm of the matrix in two decimal places.
## Program:
``` Python ```
## Register No:26015584
## Developed By:Jagadeep K
## 1-Norm of a Matrix
### import os
### os.environ["OPENBLAS_NUM_THREADS"]="1"
### import numpy as np
### mat=np.array(eval(input()))
### ans=np.linalg.norm(mat,1)
### print(f"{ans:.2f}")

## 2-Norm of a Matrix
### import os 
### os.environ["OPENBLAS_NUM_THREADS"]="1"
### import numpy as np
### mat=np.array(eval(input()))
### ans=np.linalg.norm(mat,2)
### print(round(ans,2))

# Infinity Norm of a Matrix
### import os
### os.environ["OPENBLAS_NUM_THREADS"]="1"
### import numpy as np
### mat=np.array(eval(input()))
### ans=np.linalg.norm(mat,np.inf)
### print("{:.2f}".format(ans))


## Output:
### 1-Norm of a Matrix
<br>
<img width="1210" height="860" alt="image" src="https://github.com/user-attachments/assets/5e2e045d-83c7-4bd2-baa6-9883a3568750" />
<br>
<br>

### 2-Norm of a Matrix
<br>
<img width="1122" height="817" alt="image" src="https://github.com/user-attachments/assets/80e5d843-5a64-4ca0-bc34-5b124c426a93" />
<br>
<br>

### Infinity Norm of a Matrix
<br>
<img width="1130" height="733" alt="image" src="https://github.com/user-attachments/assets/f0e958b8-82a4-4ee8-904c-5255e45e329b" />
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
