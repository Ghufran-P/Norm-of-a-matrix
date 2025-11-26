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
```
Python
# Register No: 25009482
# Developed By:Mohammed Ghufran p
# 1-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
norm1=np.linalg.norm(a,1)
print(norm1)
# 2-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
norm2=np.linalg.norm(a,2)
print(norm2)
# Infinity Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
infnorm=np.linalg.norm(a,np.inf)
print(f"{infnorm:.2f}")




```
## Output:
### 1-Norm of a Matrix
<br>
<img width="739" height="844" alt="image" src="https://github.com/user-attachments/assets/2c11e040-535c-4f5f-a17b-6cd517a5187c" />
<br>
### 2-Norm of a Matrix
<br>
<img width="649" height="841" alt="image" src="https://github.com/user-attachments/assets/8153d17d-f5a2-48c0-8b6b-b7936d259bed" />
<br>

### Infinity Norm of a Matrix
<br>
<img width="695" height="861" alt="image" src="https://github.com/user-attachments/assets/0040229a-3950-4f88-8098-1456940e011c" />

<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
