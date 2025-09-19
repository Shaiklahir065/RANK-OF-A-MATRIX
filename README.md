## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Start with the given matrix A
### Step 2: 
Use elementary row operations (swap, multiply, add rows) to make it upper triangular (like stairs shape).
### Step 3: 
Look at the first non-zero element in each row (called pivots).
### Step 4: 
The number of rows that still have at least one non-zero entry after reduction = rank.
### Step 5:
That count is the rank of the matrix.
## Program:

```python
import numpy as np
A=[[5,-3,-10],[2,2,-3],[-3,-1,5]]
rank=np.linalg.matrix_rank(A)
print(rank)
```
## Output:
<img width="1299" height="319" alt="image" src="https://github.com/user-attachments/assets/877b221d-97b9-4afb-b826-89d0c038a7cd" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

