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

# 1-Norm of a Matrix
Program to find 1-norm of a matrix.
Developed by:krithik kiran s
Register number: 212225230145
import numpy as np
print(f"{np.linalg.norm(np.array(eval(input())),1):.2f}")



# 2-Norm of a Matrix
Program to find 1-norm of a matrix.
Developed by:krithik kiran s
Register number: 212225230145
import numpy as np
print(f"{np.linalg.norm(np.array(eval(input())),2):.2f}")



# Infinity Norm of a Matrix
Program to find 1-norm of a matrix.
Developed by:krithik kiran s
Register number: 212225230145
import numpy as np
print(f"{np.linalg.norm(np.array(eval(input())),np.inf):.2f}")



```
## Output:
### 1-Norm of a Matrix
<img width="1343" height="785" alt="image" src="https://github.com/user-attachments/assets/bf7bbcf9-313d-4174-b309-6ba2b791a147" />


### 2-Norm of a Matrix
<img width="1336" height="760" alt="image" src="https://github.com/user-attachments/assets/491b1f48-6728-4b44-954a-2ab4906c061b" />


### Infinity Norm of a Matrix
<img width="1344" height="738" alt="image" src="https://github.com/user-attachments/assets/f97e0c24-64ef-469c-9326-aee8611db609" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
