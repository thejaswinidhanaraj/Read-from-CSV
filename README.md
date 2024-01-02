# Read-from-CSV

## AIM:
to write a pythom program to read contents from a csc file.

## ALGORITHM:
### Step 1:
Import pandas module as pd.
### Step 2:
Using pd.read_csv()method read the csv file.
### Step 3:
using df.head()print the first 10 rows of the csv file.
### Step 4:
Using df.tail() print the last 5 of the csv file.
### Step 5:
Using len(df.axes[])print the total no.of rows and columns with argument 0 for row and argument 1 for column.

## PROGRAM:
```
#Program to read contents from a csv file
#Developed by: THEJASWINI
#Reference number:212223110059

import pandas as pd
df=pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail(5))
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```

## OUTPUT:
![image](https://github.com/thejaswinidhanaraj/Read-from-CSV/assets/148514511/3ab82d04-0f61-4ffd-aabf-b3ef2df1c4ae)


## RESULT:
Hence the progam executed successfully.
