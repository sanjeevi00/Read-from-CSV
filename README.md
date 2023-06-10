# Read-from-CSV

## AIM:
To write a program for reading the csv file content.
## ALGORITHM:
### Step 1:
Load the CSV into a DataFrame

### Step 2:
Print the number of contents to be displayed using df.head().

### Step 3:
The number of row returned is defined in pandas option settings.

### Step 4:
Check your systems maximun column with the pd.options.display.max_columun statement.

### Step 5:
Increase the maximum number of rows to display the entire DataFrame.

## PROGRAM:
```python
"""
Developed by: Sanjeevi J
Register no: 212222110040
"""
import pandas as pd
df=pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("rows",df.axes[0])
print("columns",df.axes[1])
print("no of rows",len(df.axes[0]))
print("no of rows",len(df.axes[1]))
```
## OUTPUT:
![image](https://github.com/sanjeevi00/Read-from-CSV/assets/121484976/3a943294-72d4-4407-911b-63c36d762dcd)

## RESULT:
Thus the program executed successfully for read csv file.
