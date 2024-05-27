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
# Register No: MADHUMITHA V
# Developed By: 2305002013
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)


# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix:
![Screenshot 2024-05-27 094947](https://github.com/Madhumitha2006/Norm-of-a-matrix/assets/155508589/9dfdfbf6-b2f2-4004-ad87-bcf9109cdd4d)


### 2-Norm of a Matrix:
![Screenshot 2024-05-27 095038](https://github.com/Madhumitha2006/Norm-of-a-matrix/assets/155508589/f221c7b8-fd4b-410a-9ae3-a78b269bfaa9)


### Infinity Norm of a Matrix:
![Screenshot 2024-05-27 095136](https://github.com/Madhumitha2006/Norm-of-a-matrix/assets/155508589/f63e8b5e-002f-42c4-97db-00539f679ee1)



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.

