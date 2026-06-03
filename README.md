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
# Register No:212225040150
# Developed By:Jeffrin dino g.v
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
<img width="1241" height="1755" alt="image" src="https://github.com/user-attachments/assets/44ba1d98-3468-4166-9c9c-63b8df1821b9" />


### 2-Norm of a Matrix
<img width="1241" height="1755" alt="image" src="https://github.com/user-attachments/assets/92924f3b-9c9e-4f7a-ba09-b1e56e9865de" />


### Infinity Norm of a Matrix
<img width="1241" height="1755" alt="image" src="https://github.com/user-attachments/assets/26631a03-4160-4e95-b22d-4ea971b30e45" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
