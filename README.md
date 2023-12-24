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
# Register No: 23008005
# Developed By: Mohamed Anas O.I
# 1-Norm of a Matrix

import numpy as np
mat =np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix='{:.2f}'.format(ans)
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

![Screenshot 2023-12-24 185859](https://github.com/Anas536/Norm-of-a-matrix/assets/139841834/46f5d2ad-fc15-4c99-a567-8180c4f7a2e8)


### 2-Norm of a Matrix
![Screenshot 2023-12-24 185831](https://github.com/Anas536/Norm-of-a-matrix/assets/139841834/2cc9a190-68c0-46e0-b7a8-0e774b387bd7)


### Infinity Norm of a Matrix
![Screenshot 2023-12-24 185921](https://github.com/Anas536/Norm-of-a-matrix/assets/139841834/29b8fa54-5839-49d2-a928-1c869039f753)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
