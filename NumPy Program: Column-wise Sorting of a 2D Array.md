# NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾 Program
```
import numpy as np
n1=np.array(eval(input()))
n2=np.sort(n1,axis=0)
print("Given array")
print(f" {n1}\n ")
print(n2)
```

## Output
<img width="1097" height="711" alt="image" src="https://github.com/user-attachments/assets/a643cc10-d1b5-42fd-ae29-82d9fea10694" />

## Result
Thus,the given Python Program has been executed successfully.
