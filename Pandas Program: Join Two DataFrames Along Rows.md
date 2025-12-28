# 🧪 Pandas Program: Join Two DataFrames Along Rows

## 🎯 AIM

To write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.

---

## 🧠 ALGORITHM

1. **Import Libraries**: Import the `pandas` library.
2. **Create First DataFrame**: Use a dictionary to create `student_data1`.
3. **Create Second DataFrame**: Use another dictionary to create `student_data2`.
4. **Concatenate DataFrames**: Use `pd.concat()` with `axis=0` to concatenate both DataFrames row-wise.
5. **Display Result**: Print the new combined DataFrame.

---

## 💻 Program
```
import pandas as pd

d1 = eval(input())
d2 = eval(input())

df1 = pd.DataFrame(d1)
df2 = pd.DataFrame(d2)

print("Original DataFrames:")
print(df1)
print("-------------------------------------")
print(df2)
result = pd.concat([df1, df2], axis=1)

print("\nJoin the said two dataframes along columns:")
print(result)
```
## Output
<img width="1080" height="804" alt="530398162-90539a0b-58c0-4430-882a-43d8c5635f1e" src="https://github.com/user-attachments/assets/56516c56-9e50-4061-be7b-412c038b5b62" />


## Result
Thus,the given Python Program has been executed successfully.
