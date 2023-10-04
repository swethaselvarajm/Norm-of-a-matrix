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
# Register No: 212222230155
# Developed By: SWETHA.S
# 1-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,1)
norm="{:.2f}".format(soln)
print(norm)

# 2-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,2)
norm="{:.2f}".format(soln)
print(norm)

# Infinity Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,np.inf)
norm="{:.2f}".format(soln)
print(norm)
```
## Output:
### 1-Norm of a Matrix
![Screenshot 2023-10-04 133644](https://github.com/swethaselvarajm/Norm-of-a-matrix/assets/119525603/0b410edc-3319-4e78-bb0b-95807705436b)


### 2-Norm of a Matrix
![Screenshot 2023-10-04 133657](https://github.com/swethaselvarajm/Norm-of-a-matrix/assets/119525603/da29072b-9b38-4438-88f7-ab35a64a48ad)

### Infinity Norm of a Matrix
![Screenshot 2023-10-04 133708](https://github.com/swethaselvarajm/Norm-of-a-matrix/assets/119525603/1c6e392c-50ca-471c-8f46-08c695bfa73e)

## Result:
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.


### Infinity Norm of a Matrix
<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
