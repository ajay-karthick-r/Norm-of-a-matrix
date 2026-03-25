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
# Register No:212225230007
# Developed By:Ajay Karthick R
# 1-Norm of a Matrix

import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(one_matrix))



# 2-Norm of a Matrix
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1" 
import numpy as np
matrix=eval(input()) 
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix)) 



# Infinity Norm of a Matrix
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"  
import numpy as np
matrix=eval(input()) 
inf_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(inf_matrix))  




```
## Output:
### 1-Norm of a Matrix
<img width="761" height="199" alt="image" src="https://github.com/user-attachments/assets/1ed0b909-d832-4a20-bba0-15df3396e759" />


### 2-Norm of a Matrix
<img width="638" height="219" alt="image" src="https://github.com/user-attachments/assets/be02c599-eae2-48ee-847e-0170c3bfa4d7" />


### Infinity Norm of a Matrix
<img width="678" height="162" alt="image" src="https://github.com/user-attachments/assets/4651dd61-3785-4b31-bb51-308894727e7a" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
