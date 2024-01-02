# Read-from-CSV

## AIM:

## ALGORITHM:
### Step 1:
Import pandas as pd.
### Step 2:
Import pandas as pd.
### Step 3:
Use head and tail method to get the required contents from the file.
### Step 4:
Use len() method to get the number of rows and columns.
### Step 5:
Print the output:
## PROGRAM:
``
# Program to read a file from csv
# Developed by:Reklies J
# Register number:212223110041

import pandas as pd
f=pd.read_csv("nba.csv")
print(f.head(10))
print(f.tail())
print('Row:',len(f.axes[0]))
print('Col:',len(f.axes[1]))
```
## OUTPUT:
![image](https://github.com/Reklies/Read-from-CSV/assets/147139232/843ab60b-2e89-4ecb-8242-d2f1a1db5278)

## RESULT:
Thus a python program to read the contents of a CSV file has been executed successfully.
