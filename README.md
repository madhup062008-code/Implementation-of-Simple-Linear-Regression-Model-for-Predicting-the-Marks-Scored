# Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored

## AIM:
To write a program to predict the marks scored by a student using the simple linear regression model.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. Import required libraries and prepare input-output data (X and Y).
2. Create a Linear Regression model and train it using the dataset.
3. Extract slope and intercept, then predict output for a given input.
4. Plot actual data points and the regression line for visualization. 
. 

## Program:
```
/*
Program to implement the simple linear regression model for predicting the marks scored.

import numpy as np
import matplotlib.pyplot as plt
from sklearn.linear_model import LinearRegression


X = np.array([1, 2, 3, 4, 5]).reshape(-1, 1)
Y = np.array([35, 50, 65, 70, 85])


model = LinearRegression()

model.fit(X, Y)

m = model.coef_[0]
b = model.intercept_

print("Slope (m):", m)
print("Intercept (b):", b)

x_input = float(input("Enter hours studied: "))
predicted_marks = model.predict([[x_input]])
print("Predicted Marks:", predicted_marks[0])

Y_pred = model.predict(X)

plt.scatter(X, Y, label="Actual Data")
plt.plot(X, Y_pred, label="Regression Line")
plt.xlabel("Hours Studied")
plt.ylabel("Marks Scored")
plt.title("Simple Linear Regression (Using sklearn)")
plt.legend()
plt.show()

Developed by: MADHU .P
RegisterNumber: 212225040215
*/
```

## Output:
<img width="1062" height="659" alt="WhatsApp Image 2026-04-21 at 11 18 59 AM" src="https://github.com/user-attachments/assets/2f40ead1-4908-4213-b9b2-1a3060eedcac" />


## Result:
Thus the program to implement the simple linear regression model for predicting the marks scored is written and verified using python programming.
