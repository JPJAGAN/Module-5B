## 2. NumPy Program: Find Indices Where Elements in Array x are Greater Than or Equal to Corresponding Elements in Array y
## Aim
To write a Python program using NumPy that finds the indices where elements in array x are greater than or equal to their corresponding elements in array y.

## Algorithm
Import NumPy: Import the NumPy library.
Define Arrays: Define two NumPy arrays, x and y, with the same shape (i.e., same number of elements).
Use Boolean Indexing:
x > y gives a boolean array where elements of x are greater than y.
x == y gives a boolean array where elements of x are equal to y.
Find Indices: Use np.where() to get the indices where the conditions x >= y are satisfied.
Print Indices: Print the indices where the condition holds true.
## Program
```
import numpy as np
x=np.array(eval(input()))
y=np.array(eval(input()))
gt=np.where(x>y)
eq=np.where(x==y)
print(gt)
print(eq)Output
```
## Output

<img width="1043" height="231" alt="{B1CF5632-B821-4EB2-97A7-FCEF4A1CF2B0}" src="https://github.com/user-attachments/assets/a9c6657f-ddc9-4c1d-b299-167687ce5016"/>

## Result
Thus the program that finds the indices where elements in array x are greater than or equal to their corresponding elements in array y is executed successfully.
