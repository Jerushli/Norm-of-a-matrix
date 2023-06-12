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
# Register No:212222240039
# Developed By:JERUSHLIN JOSE J B
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
print("{:.2f}".format(ans))



# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
print("{:.2f}".format(ans))


# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))




```
## Output:
### 1-Norm of a Matrix


![image](https://github.com/Jerushli/Norm-of-a-matrix/assets/120041243/2324ebfc-bedb-4e2b-b777-71661e5053a9)





### 2-Norm of a Matrix

![image](https://github.com/Jerushli/Norm-of-a-matrix/assets/120041243/b48304e6-64c8-4298-9ddd-46aacca76ef3)





### Infinity Norm of a Matrix




![image](https://github.com/Jerushli/Norm-of-a-matrix/assets/120041243/d5c2ed3f-7f99-47db-8095-b9cc318b2273)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
