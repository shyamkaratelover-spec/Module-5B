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

Add code here
~~~
import pandas as pd

student_data1 = {
    'Name': ['Alex', 'Amy', 'Allen'],
    'Age': [20, 21, 19]
}

student_data2 = {
    'Name': ['Brian', 'Bella', 'Ben'],
    'Age': [22, 20, 21]
}

df1 = pd.DataFrame(student_data1)
df2 = pd.DataFrame(student_data2)

result = pd.concat([df1, df2], axis=0)

print(result)
~~~
## Output

<img width="1574" height="985" alt="Screenshot 2025-10-20 155316" src="https://github.com/user-attachments/assets/6ba30e09-104f-4ee3-8bb9-fd747f1a8f69" />


## Result
The Pandas program successfully joins two DataFrames along rows (row-wise concatenation) and assign all data to a new DataFrame.
