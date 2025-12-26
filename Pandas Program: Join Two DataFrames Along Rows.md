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
a=pd.DataFrame(eval(input()))
b=pd.DataFrame(eval(input()))
print("Original DataFrames:")
print(a)
print(b)
merged_data = pd.merge(a,b,on='student_id')
print("Merged data (inner join):")
print(merged_data)
```
## Output
<img width="1421" height="828" alt="image" src="https://github.com/user-attachments/assets/8375a6be-5a0d-40ad-b4b5-9bdf9ef551c7" />

## Result
Thus,the given Python Program has been executed successfully.
