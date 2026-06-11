## 1. NumPy Program: Column-wise Sorting of a 2D Array
## Aim
To write a NumPy program that sorts the elements in each column of a given 2D array in ascending order.

## Algorithm
Import NumPy: Start by importing the NumPy library.
Get Input: Accept a 2D NumPy array from the user.
Sort Column-wise: Use the np.sort() function with axis=0 to sort each column in ascending order.
Store Result: Store the sorted result in a new array.
Display Output: Print the original array and the column-wise sorted array.
## Program
```
import numpy as np
arr=np.array(eval(input()))
print("Given array")
print(arr)
print()
print(np.sort(arr,axis=0))
```
## Output

<img width="948" height="394" alt="{CD30FEDA-17B5-43D5-9AB2-91AFCAC6FF36}" src="https://github.com/user-attachments/assets/e9c6a2cf-de95-4bba-ac7a-d7d05d05ff89" />

## Result
Thus the program that sorts the elements in each column of a given 2D array in ascending order is executed successfully.
