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
# Register No:212225220032
# Developed By:GEETHA SHRI.G
# 1-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()),dtype=float)
norm=np.linalg.norm(mat,1)
print(f"{norm:.2f}")
```



# 2-Norm of a Matrix
```
import numpy as np
A=eval(input())
A=np.array(A,dtype=float)
norm=np.linalg.norm(A,2)
print(f"{norm:.2f}")

```



# Infinity Norm of a Matrix

```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm="{:.2f}".format(ans)
print(Norm)


```
## Output:
### 1-Norm of a Matrix
<img width="1245" height="357" alt="Screenshot 2026-02-12 133828" src="https://github.com/user-attachments/assets/656e30be-7209-4212-bf64-9434059c06fb" />


### 2-Norm of a Matrix
<img width="1239" height="395" alt="Screenshot 2026-02-12 133844" src="https://github.com/user-attachments/assets/b499b30b-0301-4c3c-90e5-0b69695dfbd7" />


### Infinity Norm of a Matrix
<img width="1260" height="353" alt="Screenshot 2026-02-12 133904" src="https://github.com/user-attachments/assets/f63e5a3e-5f44-4143-a601-dd073efa659a" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
