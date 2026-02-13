# Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored

## AIM:
To write a program to predict the marks scored by a student using the simple linear regression model.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. 
2. 
3. 
4. 

## Program:
```

import numpy as np
import matplotlib.pyplot as plt
from sklearn.linear_model import LinearRegression

x = np.array([1,2,3,4,5]).reshape(-1,1)
y = np.array([40,50,60,70,80])

model = LinearRegression()
model.fit(x,y)

slope = model.coef_[0]
intercept = model.intercept_
print(slope)
print(intercept)

plt.scatter(x,y,color="blue")
plt.plot(x,model.predict(x),color="red")
plt.xlabel("hours studied")
plt.ylabel("marks obtained")
plt.title("Linear regression")
plt.legend("")
plt.grid(color="yellow")
plt.show()
/*
Program to implement the simple linear regression model for predicting the marks scored.
Developed by: siva R
RegisterNumber:  25007668
*/
```

## Output:
![simple linear regression model for predicting the marks scored](sam.png)
<img width="1314" height="626" alt="ml git 2 1" src="https://github.com/user-attachments/assets/7cae73cf-013e-4d7a-b9c0-2a5d3fbcc3d8" />
<img width="863" height="667" alt="ml git 2 2" src="https://github.com/user-attachments/assets/3e6c30c6-92ec-489c-b68a-33656da598e7" />


## Result:
Thus the program to implement the simple linear regression model for predicting the marks scored is written and verified using python programming.
