## 3. NumPy Program: Replace the Second Column in a 2D Array
## Aim
To write a NumPy program that deletes the second column from a given 2D array and inserts a new column at the same position.

## Algorithm
Import NumPy: Start by importing the NumPy library.
Get Input: Get a 2D NumPy array and a new column (as another array) from the user.
Delete Column: Use np.delete() to remove the second column (index 1) from the original array.
Insert Column: Use np.insert() to insert the new column at the second column's original position.
Display Result: Print the updated array with the replaced column.
## Program
```
import numpy as np

a=np.array(eval(input()))
b=np.array(eval(input()))
print("Printing Original array")
print(a)
print("Array after deleting column 2 on axis 1")
c=np.delete(a,1,axis=1)
print(c)
print("Array after inserting column 2 on axis 1")
print(np.insert(c,1,b,axis=1))
```
## Output

<img width="1040" height="331" alt="{EEDE61BF-0348-4993-B4CA-D13D96AC0E40}" src="https://github.com/user-attachments/assets/71a45950-63ff-4ca9-a139-3e4b199d4c03" />

## Result
Thus the program that deletes the second column from a given 2D array and inserts a new column at the same position is executed successfully.
