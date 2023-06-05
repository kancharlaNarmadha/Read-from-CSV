# Read-from-CSV

## AIM:
To read files from csv files using python program.

## ALGORITHM:

### Step 1: 
Start the python.

### Step 2: 
Import pandas

### Step 3: 
Mention the CSV file which is to be read.

### Step 4: 
Read the contents of the CSV file using df.read function.

### Step 5:
End the program.

## PROGRAM:
```
#Devloped By: KANCHARLA NARMADHA

#Ref no: 212222110016

import pandas as pd
df = pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("column", len(df.axes[0]))
print("rows", len(df.axes[1]))
```

## OUTPUT:

![PYTH OUT UT 6](https://github.com/kancharlaNarmadha/Read-from-CSV/assets/119559316/4cfa9315-541b-4e91-b9f1-0ac0c8773305)


## RESULT:
A python program to read data from CSV files has been created successfully.
