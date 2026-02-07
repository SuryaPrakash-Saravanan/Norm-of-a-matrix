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
# Register No:25014536
# Developed By:Surya Prakash S
# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm = "{:.2f}".format(ans)
print(Norm)


# 2-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)




# Infinity Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)





```
## Output:
### 1-Norm of a Matrix
<img width="818" height="196" alt="Screenshot 2026-02-07 085412" src="https://github.com/user-attachments/assets/44732e7f-a529-4e0e-9903-f3cad8140de2" />

<br>
<br>
<br>

### 2-Norm of a Matrix
<img width="811" height="229" alt="Screenshot 2026-02-07 085418" src="https://github.com/user-attachments/assets/d6136490-bcd6-440c-9b22-27eac408933e" />

<br>
<br>
<br>

### Infinity Norm of a Matrix
<img width="820" height="199" alt="Screenshot 2026-02-07 085424" src="https://github.com/user-attachments/assets/35488b57-fab1-4e7b-b365-17d6d2c949f7" />

<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
