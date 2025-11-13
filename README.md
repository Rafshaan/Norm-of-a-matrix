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
# Register No:21224230214
#Developed By: rafshaan ahmed
 #1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)


# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)





```
## Output:
### 1-Norm of a Matrix
<br>
<img width="1032" height="190" alt="image" src="https://github.com/user-attachments/assets/0c7d2c3b-dab0-49ae-ada0-8bba40842f67" />

<br>
<br>

### 2-Norm of a Matrix
<br>
<img width="1039" height="216" alt="image" src="https://github.com/user-attachments/assets/cc7746e8-bd6b-4776-af81-08c9d6d93287" />

<br>
<br>

### Infinity Norm of a Matrix
<br>
<img width="1042" height="180" alt="image" src="https://github.com/user-attachments/assets/762ef713-16ba-4090-b8e8-2708e292f360" />

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
