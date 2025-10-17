## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Start with the given matrix A
### Step 2: 
Perform row operations (swap, multiply, or add multiples of rows) to simplify the matrix.
### Step 3: 
Convert the matrix into row-echelon form (upper triangular form where all entries below the main diagonal are zero).
### Step 4: 
Identify all non-zero rows in the row-echelon form.
### Step 5:
The number of non-zero rows is the rank of the matrix.
## Program:

```python
#Developed by:shaik lahir 
#RegisterNumber:212224240148

import numpy as np
A=[[5,-3,-10],[2,2,-3],[-3,-1,5]]
rank=np.linalg.matrix_rank(A)
print(rank)
```
## Output:
<img width="1299" height="319" alt="image" src="https://github.com/user-attachments/assets/877b221d-97b9-4afb-b826-89d0c038a7cd" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

