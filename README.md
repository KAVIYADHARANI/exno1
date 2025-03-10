# Exno:1
Data Cleaning Process

# AIM
To read the given data and perform data cleaning and save the cleaned data to a file.

# Explanation
Data cleaning is the process of preparing data for analysis by removing or modifying data that is incorrect ,incompleted , irrelevant , duplicated or improperly formatted. Data cleaning is not simply about erasing data ,but rather finding a way to maximize datasets accuracy without necessarily deleting the information.

# Algorithm
STEP 1: Read the given Data

STEP 2: Get the information about the data

STEP 3: Remove the null values from the data

STEP 4: Save the Clean data to the file

STEP 5: Remove outliers using IQR

STEP 6: Use zscore of to remove outliers

# Coding and Output

'''
NAME : KAVIYA D
REG NO : 212223040089
'''

'''
import pandas as pd
exp=pd.read_csv("/content/SAMPLEIDS.csv")
exp.head()
'''
![image](https://github.com/user-attachments/assets/d81ccd35-cbb6-445d-babc-add34c44cfad)

'''
exp.head(5)
'''
![image](https://github.com/user-attachments/assets/95f952f0-1062-437c-bf00-e8a6e03e924f)


```
exp.tail(5)
```
![image](https://github.com/user-attachments/assets/c8fe62ca-b6e1-4c52-bb95-1c3b6033659a)


# Result
          <<include your Result here>>
