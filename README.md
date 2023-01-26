# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the respective norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
### 1-Norm of a Matrix
```Python
#Register No: 22009286
#Developed By: Sanjay Ragavendar M K

import numpy as np

mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_matrix='{:.2f}'.format(ans)
print(norm_matrix)
```

### 2-Norm of a Matrix
```Python
#Register No: 22009286
#Developed By: Sanjay Ragavendar M K

import numpy as np

mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_mat='{:.2f}'.format(ans)
print(norm_mat)
```

### Infinity Norm of a Matrix
```Python
#Register No: 22009286
#Developed By: Sanjay Ragavendar M K

import numpy as np

mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_mat='{:.2f}'.format(ans)
print(norm_mat)
```
## Output:
### 1-Norm of a Matrix

![image](https://user-images.githubusercontent.com/91368803/214784851-a714c167-b722-4fa9-993e-e970e7de31c5.png)

### 2-Norm of a Matrix

![image](https://user-images.githubusercontent.com/91368803/214784917-57ad6124-2d4f-44f6-896c-1a68921aa874.png)

### Infinity Norm of a Matrix

![image](https://user-images.githubusercontent.com/91368803/214784969-521ce298-606f-4848-9ed2-fa651a8655ba.png)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
