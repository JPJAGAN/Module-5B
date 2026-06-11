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
