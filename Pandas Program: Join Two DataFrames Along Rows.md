#  Pandas Program: Join Two DataFrames with matching records

##  AIM
Create a Pandas program to join the two dataframes with matching records from both sides where available.
---

##  ALGORITHM

1. **Import Libraries**: Import the `pandas` library.
2. **Create First DataFrame**: Use a dictionary to create `student_data1`.
3. **Create Second DataFrame**: Use another dictionary to create `student_data2`.
4. **Concatenate DataFrames**: Use `pd.merge()` to concatenate both DataFrames matching.
5. **Display Result**: Print the new combined DataFrame.

---

## Program
~~~
import pandas as pd
a=pd.DataFrame(eval(input()))
a1=pd.DataFrame(eval(input()))
print("Original DataFrames:")
print(a)
print(a1)
print("Merged data (outer join):")
df=pd.merge(a,a1,on='s_id',how='outer')
print(df)
~~~
## OUTPUT
<img width="493" height="409" alt="image" src="https://github.com/user-attachments/assets/2d152a17-1679-4cc7-9cfd-5008de13ea5b" />

## Result
thus the program is executed succesfully!!
