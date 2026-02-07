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
# Register No:212225230127
# Developed By:N.Kanishka
# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)




# 2-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)



# Infinity Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)





```
## Output:
### 1-Norm of a Matrix

<img width="1832" height="957" alt="Maths Exp-7(a)" src="https://github.com/user-attachments/assets/b33d27c9-2f10-4a31-81ec-65fcab3556ed" />


### 2-Norm of a Matrix

<img width="1839" height="956" alt="Maths Exp-7(b)" src="https://github.com/user-attachments/assets/1de8e1ff-0e55-4bfe-9741-9ded6d3b4b84" />


### Infinity Norm of a Matrix

<img width="1828" height="960" alt="Maths Exp-7(c)" src="https://github.com/user-attachments/assets/574c4261-f7ed-4f5d-8cce-27616f5c0439" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
