# Pandas Program: Create and Display a DataFrame with Custom Index Labels

## 🎯 Aim

To create and display a **DataFrame** using the **Pandas** library in Python from a given dictionary, and apply specific index labels to the rows.

---

## 🧠 Algorithm

1. **Import Libraries**: Import the required libraries – `pandas` and `numpy`.
2. **Create Dictionary**: Define a dictionary `exam_data` with keys: `'name'`, `'score'`, `'attempts'`, and `'qualify'`.
3. **Index Labels**: Create a list of custom index labels called `labels`.
4. **Create DataFrame**: Use `pd.DataFrame()` to create the DataFrame by passing the dictionary and index labels.
5. **Display Output**: Display the DataFrame using `print()` or by simply calling the DataFrame variable.

---

## 💻 Program
```
import pandas as pd

# Read input dictionaries
d1 = eval(input())
d2 = eval(input())

# Create DataFrames
df1 = pd.DataFrame(d1)
df2 = pd.DataFrame(d2)

print("Original DataFrames:")
print(df1)
print("-------------------------------------")
print(df2)

# Join along columns
result = pd.concat([df1, df2], axis=1)

print("\nJoin the said two dataframes along columns:")
print(result)
```
## Output
<img width="1080" height="804" alt="Screenshot 2025-12-26 230823" src="https://github.com/user-attachments/assets/90539a0b-58c0-4430-882a-43d8c5635f1e" />

<img width="829" height="705" alt="image" src="https://github.com/user-attachments/assets/2c3bfae5-bf0d-48d0-9e7f-48c41b956bfd" />

## Result
