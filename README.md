# Ex.No: 01A PLOT A TIME SERIES DATA
###  Date: 12-08-25

# AIM:
To Develop a python program to Plot a time series data (population/ market price of a commodity
/temperature.
# ALGORITHM:
1. Import the required packages like pandas and matplot
2. Read the dataset using the pandas
3. Calculate the mean for the respective column.
4. Plot the data according to need and can be altered monthly, or yearly.
5. Display the graph.
# PROGRAM:
```
Developed by:UDHAYA PRAKASH V
REG NO:212224240177
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import warnings
warnings.filterwarnings('ignore')
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
from sklearn.metrics import mean_squared_error, mean_absolute_error, r2_score
from sklearn.preprocessing import StandardScaler
data=pd.read_csv("C:\\Users\\admin\\Documents\\time series dataset\\archive (3).zip")
data
plt.figure(figsize=(8,5))
sns.histplot(data['Price'], kde=True, color='skyblue', bins=30)
plt.title("Distribution of House Prices", fontsize=14, weight='bold')
plt.show()
```
# OUTPUT:
<img width="840" height="548" alt="Screenshot (157)" src="https://github.com/user-attachments/assets/1b6b018f-251d-4e21-a4d5-14bc3c37ab2c" />







# RESULT:
Thus we have created the python code for plotting the time series of given data.
