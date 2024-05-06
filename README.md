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
# Register No:212223240183
# Developed By:Visalan H
# 1-Norm of a Matrix
```
import numpy as np
a=np.array(eval(input()))
b=np.linalg.norm(a,1)
print(f"{b:.2f}")
```
# 2-Norm of a Matrix
```
import numpy as np
a=np.array(eval(input()))
b=np.linalg.norm(a,2)
print(f"{b:.2f}")
```
# Infinity Norm of a Matrix
```
import numpy as np
a=np.array(eval(input()))
b=np.linalg.norm(a,np.inf)
print(f"{b:.2f}")
```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/Visalan-H/Norm-of-a-matrix/assets/152077751/0cdc6a81-62bc-40c6-a25f-f026f6d072e6)
### 2-Norm of a Matrix
![image](https://github.com/Visalan-H/Norm-of-a-matrix/assets/152077751/1de2f060-4c14-4edd-8d6b-95cbb0323fc8)
### Infinity Norm of a Matrix
![image](https://github.com/Visalan-H/Norm-of-a-matrix/assets/152077751/594b3928-1aae-47e0-bb2e-e7b346a20fe6)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
