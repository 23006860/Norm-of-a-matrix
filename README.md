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
# Register No: RAHUL.V
# Developed By: 23006860
# 1-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: RAHUL.V
RegisterNumber: 23006860
'''
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))


# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: RAHUL.V
RegisterNumber: 23006860
'''
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))



# Infinity Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: RAHUL.V
RegisterNumber: 23006860
'''
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))





```
## Output:
### 1-Norm of a Matrix
![Screenshot 2023-12-27 075744](https://github.com/23006860/Norm-of-a-matrix/assets/139841752/32058285-6385-432c-a811-a8cc26eb44cf)

### 2-Norm of a Matrix
![Screenshot 2023-12-27 080141](https://github.com/23006860/Norm-of-a-matrix/assets/139841752/3aae4f77-8782-4456-a2c8-579833fce6a2)

### Infinity Norm of a Matrix
![Screenshot 2023-12-27 075851](https://github.com/23006860/Norm-of-a-matrix/assets/139841752/580e2481-2bb6-472a-bcbe-c12d48dc3b62)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
