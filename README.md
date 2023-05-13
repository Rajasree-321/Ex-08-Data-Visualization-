# Ex-08-Data-Visualization-

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

df=pd.read_csv("/content/Superstore.csv",encoding='windows-1252')

df.head()

![image](https://github.com/Rajasree-321/Ex-08-Data-Visualization-/assets/96918911/c644d94c-dfbe-498f-824d-150c8236c3ea)

df.info()

![image](https://github.com/Rajasree-321/Ex-08-Data-Visualization-/assets/96918911/51371463-51c4-47fb-9e57-190b33e682b4)

df.isnull().sum()

![image](https://github.com/Rajasree-321/Ex-08-Data-Visualization-/assets/96918911/833d0fdf-15b2-4422-b2c9-bf14d91935f3)

# OUPUT

![image](https://github.com/Rajasree-321/Ex-08-Data-Visualization-/assets/96918911/060a2212-5b80-4c6e-9d6a-583251e6326f)

![image](https://github.com/Rajasree-321/Ex-08-Data-Visualization-/assets/96918911/94734e04-c0d2-4e00-942c-870565898758)

![image](https://github.com/Rajasree-321/Ex-08-Data-Visualization-/assets/96918911/bc74f073-5c2e-4c85-a443-0d0374568242)

![image](https://github.com/Rajasree-321/Ex-08-Data-Visualization-/assets/96918911/6d71d55f-9860-45e4-9c9d-3cb1ab232578)

![image](https://github.com/Rajasree-321/Ex-08-Data-Visualization-/assets/96918911/3d128b07-e738-42fb-bb49-8b530e1dd0d8)

![image](https://github.com/Rajasree-321/Ex-08-Data-Visualization-/assets/96918911/7f5a47e6-efec-40a2-93b1-c974e40e1f1a)

![image](https://github.com/Rajasree-321/Ex-08-Data-Visualization-/assets/96918911/ab1dc60b-66f5-498b-afef-33094358cff4)

![image](https://github.com/Rajasree-321/Ex-08-Data-Visualization-/assets/96918911/55bff0f8-d91f-4cf7-88f0-d9d28c315bbc)

![image](https://github.com/Rajasree-321/Ex-08-Data-Visualization-/assets/96918911/231e8f82-1b13-4008-932e-c169d3c3e5d7)


