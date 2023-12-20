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
# Register No: 212223230010
# Developed By: AKASH KUMAR M.
# 1-Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))



# 2-Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))




# Infinity Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))




```
## Output:
### 1-Norm of a Matrix
![output](https://github.com/akash7812/Norm-of-a-matrix/assets/146819826/f3297175-a2eb-40e7-8e9f-d46c4bf31645)


### 2-Norm of a Matrix
![output](https://github.com/akash7812/Norm-of-a-matrix/assets/146819826/91ef09a2-158c-4ef3-b5dc-d4c16b3e3c14)


### Infinity Norm of a Matrix
![output](https://github.com/akash7812/Norm-of-a-matrix/assets/146819826/60a015eb-9fd5-4324-a4f6-c963baf55d5d)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
