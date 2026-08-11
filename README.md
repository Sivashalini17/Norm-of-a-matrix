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
# 1-Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: Siva Shalini.S
RegisterNumber: 212224240154
'''
import os
os.environ['OPENBLAS_NUM_THREADS']='1'
import numpy as np
mat=eval(input())
a=np.linalg.norm(mat,1)
print("%0.2f"%a)
```

# 2-Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: Siva Shalini.S
RegisterNumber: 212224240154
'''
import os
os.environ['OPENBLAS_NUM_THREADS']='1'
import numpy as np
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_mat="{:.2f}".format(ans)
print(norm_mat)
```

# Infinity Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: Siva Shalini.S
RegisterNumber: 212224240154
'''
import os
os.environ['OPENBLAS_NUM_THREADS']='1'
import numpy as np
mat=eval(input())
a=np.linalg.norm(mat,np.inf)
print("%0.2f"%a)
```

## Output:
### 1-Norm of a Matrix

<img width="1867" height="965" alt="image" src="https://github.com/user-attachments/assets/979b9f4f-0497-4f63-aec9-dfeb023ea397" />

### 2-Norm of a Matrix

<img width="1866" height="972" alt="image" src="https://github.com/user-attachments/assets/e9f6f988-9c23-4744-971d-59275693e160" />

### Infinity Norm of a Matrix

<img width="1855" height="981" alt="image" src="https://github.com/user-attachments/assets/5bd69618-d2cb-45e7-9bee-44e9520a3a58" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
