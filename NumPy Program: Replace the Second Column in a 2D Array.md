# NumPy Program: Replace the Second Column in a 2D Array

## 🎯 Aim
To write a **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position.

## 🧠 Algorithm
1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Get a 2D NumPy array and a new column (as another array) from the user.
3. **Delete Column**: Use `np.delete()` to remove the second column (index 1) from the original array.
4. **Insert Column**: Use `np.insert()` to insert the new column at the second column's original position.
5. **Display Result**: Print the updated array with the replaced column.

## 🧾 Program
```
import numpy as np
import ast
x=np.array(ast.literal_eval(input()))
y=np.array(ast.literal_eval(input()))
print("Printing Original array")
print(x)
print("Array after deleting column 2 on axis 1")
sampleArray=np.delete(x,1,axis=1)
print(sampleArray)

print("Array after inserting column 2 on axis 1")
sampleArray=np.insert(sampleArray,1,y,axis=1)
print(sampleArray)
```
## Output
<img width="1464" height="868" alt="image" src="https://github.com/user-attachments/assets/a2cb7ed0-4d9a-4ab1-823d-347458d7ba3d" />

## Result
Thus,the given Python Program has been executed successfully.
