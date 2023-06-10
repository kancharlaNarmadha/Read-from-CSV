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
df=pd.read_csv("/content/nba.csv")
print(df.head(10))
print(df.tail())
print("no of rows",df.axes[0])
print("no of columns",df.axes[1])
print("no of rows",len(df.axes[0]))
print("no of columns",len(df.axes[1]))
```

## OUTPUT:

![pyth last one](https://github.com/kancharlaNarmadha/Read-from-CSV/assets/119559316/129a3250-d5b2-467d-9c92-2a7ba97a9e4f)




## RESULT:
A python program to read data from CSV files has been created successfully.
