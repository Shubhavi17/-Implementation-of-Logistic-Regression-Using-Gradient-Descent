# Implementation-of-Logistic-Regression-Using-Gradient-Descent

## AIM:
To write a program to implement the the Logistic Regression Using Gradient Descent.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm


## Program:
```
/*
Program to implement the the Logistic Regression Using Gradient Descent.
Developed by: Shubhavi.M
RegisterNumber: 212223040199
import pandas as pd
from sklearn.tree import DecisionTreeClassifier,plot_tree
from sklearn.preprocessing import LabelEncoder
import matplotlib.pyplot as plt
df=pd.read_csv('/content/Mammal_Cart.csv')
data=df.copy()
data.describe()
label_encoder=LabelEncoder()
data['Toothed']=label_encoder.fit_transform(data['Toothed'])
data['Hair']=label_encoder.fit_transform(data['Hair'])
data['Breathes']=label_encoder.fit_transform(data['Breathes'])
data['Legs']=label_encoder.fit_transform(data['Legs'])
data['Species']=label_encoder.fit_transform(data['Species'])
x=data.drop('Species',axis=1)
y=data['Species']
clf=DecisionTreeClassifier(criterion="entropy")
clf.fit(x,y)
plt.figure(figsize=(18,6))
plot_tree(clf,feature_names=x.columns,class_names=['Reptiles','Mammal'],filled=True)
plt.show()

*/
```

## Output:
![Screenshot 2024-04-02 155941](https://github.com/Shubhavi17/-Implementation-of-Logistic-Regression-Using-Gradient-Descent/assets/150005085/50736f21-f1a7-4f9b-9490-0742e2fd7213)
![Screenshot 2024-04-02 155948](https://github.com/Shubhavi17/-Implementation-of-Logistic-Regression-Using-Gradient-Descent/assets/150005085/863aa8d9-dd14-472c-84e1-36292c9d5994)
![Screenshot 2024-04-02 155958](https://github.com/Shubhavi17/-Implementation-of-Logistic-Regression-Using-Gradient-Descent/assets/150005085/f5353ba8-0858-4284-8aca-7c89cc409570)





## Result:
Thus the program to implement the the Logistic Regression Using Gradient Descent is written and verified using python programming.

