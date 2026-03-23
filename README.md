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
# Register No:25010344
# Developed By:N LAXMI PRIYA
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)




# 2-Norm of a Matrix
#The L2 norm (or Euclidean norm) of a vector measures the "length" or "magnitude" of the vector. Or it is the square root of sum of squares of all the elements
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)




# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)





```
## Output:
### 1-Norm of a Matrix
<br>
<br>
<br>






<img width="1598" height="818" alt="image" src="https://github.com/user-attachments/assets/9b0d7f38-80a3-4450-b6e2-d894f0813e95" />





### 2-Norm of a Matrix
<br>
<br>
<br>


<img width="1868" height="762" alt="image" src="https://github.com/user-attachments/assets/d68044b7-23dd-49fd-85b1-0cb6d61e8975" />





### Infinity Norm of a Matrix
<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
