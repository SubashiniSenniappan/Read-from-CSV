# Read-from-CSV

## AIM:
     To write a python program for getting the read from csv a text

## ALGORITHM:
### Step 1:
      start the python
### Step 2:
      import pandas
### Step 3:
       metion the csv file which is to be read
### Step 4:
       read the contects of the csv file usin df.read function
### Step 5:
       end the program

## PROGRAM:
       #Developed by: Subashini.S
       #Register number: 22009344
       import ppandas as pd
       f=pd.read_csv("/content/nba.csv")
       print(f.head(10))
       print(f.tail())
       print("Row:",len(f.axes[0]))
       print("col:",len(f.axes[1]))

## OUTPUT:
![fileeeeeeee](https://user-images.githubusercontent.com/119404951/215110566-c66f2aab-be79-4d85-ac42-29ea32e41662.jpg)

## RESULT:
A python program to read from csv files has been created successfully.

