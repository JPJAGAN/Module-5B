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

<img width="1043" height="231" alt="{B1CF5632-B821-4EB2-97A7-FCEF4A1CF2B0}" src="https://github.com/user-attachments/assets/a9c6657f-ddc9-4c1d-b299-167687ce5016" />

## Result
Thus the program that finds the indices where elements in array x are greater than or equal to their corresponding elements in array y is executed successfully.

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

## 4. Pandas Program: Create and Display a DataFrame with Custom Index Labels
## Aim
To create and display a DataFrame using the Pandas library in Python from a given dictionary, and apply specific index labels to the rows.

## Algorithm
Import Libraries: Import the required libraries – pandas and numpy.
Create Dictionary: Define a dictionary exam_data with keys: 'name', 'score', 'attempts', and 'qualify'.
Index Labels: Create a list of custom index labels called labels.
Create DataFrame: Use pd.DataFrame() to create the DataFrame by passing the dictionary and index labels.
Display Output: Display the DataFrame using print() or by simply calling the DataFrame variable.
## Program
```
import pandas as pd 
import numpy as np

exam_data  = {'name': ['Anastasia', 'Dima', 'Katherine', 'James', 'Emily', 'Michael', 'Matthew', 'Laura', 'Kevin','Jonas'], 
'score': [12.5, 9, 16.5, np.nan, 9, 20, 14.5, np.nan, 8, 19], 
'attempts': [1, 3, 2, 3, 2, 3, 1, 1, 2, 1], 
'qualify': ['yes', 'no', 'yes', 'no', 'no', 'yes', 'yes', 'no', 'no', 'yes']}

label=['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j'] 
df = pd.DataFrame(exam_data , index=label) 
print(df)
```
## Output

<img width="1047" height="507" alt="{13CA823E-C0C3-4C94-AEF8-92C25F408CE8}" src="https://github.com/user-attachments/assets/0eedf69e-cd22-48ff-9c9c-88b4dbb771db" />

## Result
Thus the program to create and display a DataFrame using the Pandas library in Python from a given dictionary, and apply specific index labels to the rows is executed successfully.

## 5. 🧪 Pandas Program: Join Two DataFrames Along Rows
## AIM
To write a Python program using Pandas to join two DataFrames along rows (row-wise concatenation) and assign all data to a new DataFrame.

## ALGORITHM
Import Libraries: Import the pandas library.
Create First DataFrame: Use a dictionary to create student_data1.
Create Second DataFrame: Use another dictionary to create student_data2.
Concatenate DataFrames: Use pd.concat() with axis=0 to concatenate both DataFrames row-wise.
Display Result: Print the new combined DataFrame.
## Program
```
import pandas as pd
a=eval(input())
b=eval(input())
df1=pd.DataFrame(a)
df2=pd.DataFrame(b)
print("Original DataFrames:")
print(df1)
print("-------------------------------------")
print(df2)
print()
mer=pd.concat([df1,df2])
print("Join the said two dataframes along rows:")
print(mer)
```
## Output
<img width="1042" height="675" alt="{0732781D-0E1B-4739-B915-CCD0BB8D7394}" src="https://github.com/user-attachments/assets/4f827a13-80c4-491e-96f8-22c50911b81b" />

## Result
Thus,The program has been executed successfully
