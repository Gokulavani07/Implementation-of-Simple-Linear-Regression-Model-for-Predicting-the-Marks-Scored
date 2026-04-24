# Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored

## AIM:
To write a program to predict the marks scored by a student using the simple linear regression model.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
 1.Import the standard Libraries.
 2.Set variables for assigning dataset values.
 3.Import linear regression from sklearn.
 4.Assign the points for representing in the graph.
 5.Predict the regression for marks by using the representation of the graph.
 6.Compare the graphs and hence we obtained the linear regression for the given datas.


## Program:
```
/*
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
from sklearn.metrics import mean_squared_error, mean_absolute_error


data = {
    'Hours': [2.5, 5.1, 3.2, 8.5, 3.5, 1.5, 9.2, 5.5, 8.3, 2.7],
    'Scores': [21, 47, 27, 75, 30, 20, 88, 60, 81, 25]
}

df = pd.DataFrame(data)

print(df)

X = df[['Hours']].values
Y = df['Scores'].values

Xtrain, Xtest, Ytrain, Ytest = train_test_split(X, Y, test_size=1/3, random_state=0)


reg = LinearRegression()
reg.fit(Xtrain, Ytrain)


Ypred = reg.predict(Xtest)

print("Predicted Values:", Ypred)


plt.scatter(Xtrain, Ytrain, color='orange')
plt.plot(Xtrain, reg.predict(Xtrain), color='red')
plt.title("Training Set")
plt.xlabel("Hours")
plt.ylabel("Scores")
plt.show()


plt.scatter(Xtest, Ytest, color='blue')
plt.plot(Xtest, reg.predict(Xtest), color='green')
plt.title("Test Set")
plt.xlabel("Hours")
plt.ylabel("Scores")
plt.show()


mse = mean_squared_error(Ytest, Ypred)
mae = mean_absolute_error(Ytest, Ypred)
rmse = np.sqrt(mse)

print("MSE :", mse)
print("MAE :", mae)
print("RMSE :", rmse)
Developed by: Gokulavani.R
RegisterNumber:  212225220035
*/
```

## Output:
<img width="752" height="829" alt="Screenshot 2026-04-24 151917" src="https://github.com/user-attachments/assets/7532e66e-8759-4aee-917c-394faed2adda" />
<img width="912" height="641" alt="Screenshot 2026-04-24 151946" src="https://github.com/user-attachments/assets/245e029a-a5ac-42bd-b648-e47b56f16c2c" />



## Result:
Thus the program to implement the simple linear regression model for predicting the marks scored is written and verified using python programming.
