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
# Register No:25008001
# Developed By:MAHALAKSHMI J
# 1-Norm of a Matrix
import numpy as np
A=np.array(eval(input()))
norm1=np.linalg.norm(A,1)
print(f"{norm1:.2f}")



# 2-Norm of a Matrix
import numpy as np
A=np.array(eval(input()))
norm2=np.linalg.norm(A,2)
print(f"{norm2:.2f}")




# Infinity Norm of a Matrix
import numpy as np
A=np.array(eval(input()))
normi=np.linalg.norm(A,np.inf)
print(f"{normi:.2f}")




```
## Output:
### 1-Norm of a Matrix
<img width="573" height="677" alt="Screenshot 2025-12-24 083403" src="https://github.com/user-attachments/assets/c245e95f-9008-40bd-be57-e0ea39314d8f" />


### 2-Norm of a Matrix
<img width="514" height="706" alt="Screenshot 2025-12-24 083415" src="https://github.com/user-attachments/assets/3b5ccb0e-8a06-4ff0-ab24-5c62a801eef7" />


### Infinity Norm of a Matrix
<img width="578" height="659" alt="Screenshot 2025-12-24 083431" src="https://github.com/user-attachments/assets/698af299-51fc-464e-8a41-62b60423f643" />



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
