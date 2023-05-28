# Ex-08-Data-Visualization-
[EX NO_8(Naveensan Y-212220040099).ipynb - Colaboratory.pdf](https://github.com/Naveensan123/Ex-08-Data-Visualization-/files/11585055/EX.NO_8.Naveensan.Y-212220040099.ipynb.-.Colaboratory.pdf)

## AIM
To Perform Data Visualization on the given dataset and save the data to a file. 

# Explanation
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# ALGORITHM
### STEP 1
Read the given Data
### STEP 2
Clean the Data Set using Data Cleaning Process
### STEP 3
Apply Feature generation and selection techniques to all the features of the data set
### STEP 4
Apply data visualization techniques to identify the patterns of the data.

# CODE

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sbn
df=pd.read_csv("Superstore.csv",encoding = 'windows-1252')
df.head()
df.info()
df.isnull().sum()
sbn.countplot(x=df['Segment'],data=df)
plt.title("Number of Sales in Segment")
sbn.barplot(x=df['City'],y=df['Profit'])
plt.title("Number of Profit in Cities")
sbn.countplot(x=df['Ship Mode'],data=df)
plt.title("Number of profits in Ship Mode")
sbn.boxplot(x=df['Region'], y=df['Sales'])
plt.title("Sales of Product based on Region")
sbn.scatterplot(x=df['Sales'], y=df['Profit'])
sbn.scatterplot(x=df['Sales'],y=df['Profit'],hue=df['Segment'])
sbn.scatterplot(x=df['Sales'],y=df['City'],hue=df['Profit'])
sbn.scatterplot(x=df['Sales'], y=df['Profit'])
sbn.scatterplot(x=df['Sales'],y=df['Profit'],hue=df['Segment'])

# OUPUT
[EX NO_8(Naveensan Y-212220040099).ipynb - Colaboratory.pdf](https://github.com/Naveensan123/Ex-08-Data-Visualization-/files/11585057/EX.NO_8.Naveensan.Y-212220040099.ipynb.-.Colaboratory.pdf)
![2023-05-28 (3)](https://github.com/Naveensan123/Ex-08-Data-Visualization-/assets/95761973/7c8bfbfd-e083-4ef1-b3fc-726199806ee6)
![2023-05-28 (4)](https://github.com/Naveensan123/Ex-08-Data-Visualization-/assets/95761973/180fa891-bfd4-4fc7-a739-1f7a954ea19f)
![2023-05-28 (5)](https://github.com/Naveensan123/Ex-08-Data-Visualization-/assets/95761973/992e73d8-9750-4b4d-a00e-b44c87bd2d65)
![2023-05-28 (6)](https://github.com/Naveensan123/Ex-08-Data-Visualization-/assets/95761973/17f7d6d0-f657-4fda-a804-432179ab11d5)
![2023-05-28 (7)](https://github.com/Naveensan123/Ex-08-Data-Visualization-/assets/95761973/e8a0b4dc-3da9-4517-8c60-6a7d14e850fc)
![2023-05-28 (8)](https://github.com/Naveensan123/Ex-08-Data-Visualization-/assets/95761973/3ccb62e5-24cb-4a0a-aa35-ba79b3ed66bf)
![2023-05-28 (9)](https://github.com/Naveensan123/Ex-08-Data-Visualization-/assets/95761973/5f515d06-1706-40d2-9793-609bb41e3fb6)
![2023-05-28 (10)](https://github.com/Naveensan123/Ex-08-Data-Visualization-/assets/95761973/94adb3d6-a7a7-4a57-92e4-8e1460831796)
![2023-05-28 (11)](https://github.com/Naveensan123/Ex-08-Data-Visualization-/assets/95761973/828228fb-a3fa-40e8-9914-0f2ce527a0a1)
![2023-05-28 (12)](https://github.com/Naveensan123/Ex-08-Data-Visualization-/assets/95761973/93eb88d5-c596-4beb-93f3-26afcacee3ab)
![2023-05-28 (13)](https://github.com/Naveensan123/Ex-08-Data-Visualization-/assets/95761973/d92fe85f-40c8-41c8-ba55-320e5614c40d)
![2023-05-28 (14)](https://github.com/Naveensan123/Ex-08-Data-Visualization-/assets/95761973/cf416a2c-1b5e-451c-94b6-4bf61d84036b)

# RESULT
Thus the Data Visualization for the given dataset had been executed successfully

