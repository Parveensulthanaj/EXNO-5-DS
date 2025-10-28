# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:
```
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
```

```
marks=[13,45,63,78]
student=['ABC','QOR','EFB','TOB']
plt.plot(marks,student)
plt.xlabel('Marks')
plt.ylabel('Student name')
plt.show()
```
<img width="826" height="528" alt="ds5 1" src="https://github.com/user-attachments/assets/542fb91b-8d08-431c-bb4f-a7aa10022a1a" />

```
student=['A','B','C','D']
attendence=[90,85,73,88]
plt.plot(attendence,student)
plt.xlabel('Attendence')
plt.ylabel('Student name')
plt.show()
```
<img width="823" height="536" alt="ds5 2" src="https://github.com/user-attachments/assets/4223375d-a4b0-4186-b072-cfb6f596d180" />

```
x=[10,20,30,40,50]
y=[100,200,300,400,500]
plt.scatter(x,y,label='stars',color='green',marker='*',s=30)
plt.show()
```
<img width="735" height="492" alt="ds5 3" src="https://github.com/user-attachments/assets/3b28da88-5c7e-4c63-b6a7-0f4c1090f313" />

```
x=np.arange(0,15)
y=np.arange(0,15)
x
y
plt.scatter(x,y,c='r')
plt.xlabel('X axis')
plt.ylabel('y axis')
plt.title('Scatter plot')
plt.show()
```
<img width="740" height="546" alt="ds5 4" src="https://github.com/user-attachments/assets/38f05958-ee0d-4f30-ad4d-b278a663daec" />

```
act=['eat','sleep','work','play']
slices=[3,7,8,6]
color=['r','y','g','b']
plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
```
<img width="719" height="506" alt="ds5 5" src="https://github.com/user-attachments/assets/393fc678-fcfd-4f8a-8a2c-fa5cce6b5833" />

```
feedback=['Good','excellent','Perfect','Ok']
slices=[4,10,3,8]
color=['y','r','b','g']
plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
```
<img width="630" height="490" alt="ds5 6" src="https://github.com/user-attachments/assets/af96c665-fbab-4469-bfaf-77de027b8314" />

```
x = [1, 2, 3, 4, 5]
y1 = [10, 12, 14, 16, 18]
y2 = [5, 7, 9, 11, 13]
y3 = [2, 4, 6, 8, 10]
plt.fill_between(x, y1, color='blue')
plt.fill_between(x, y2, color='green')
plt.plot(x, y1, color='red')
plt.plot(x, y2, color='black')
plt.legend(['y1','y2'])
plt.show()
```
<img width="875" height="509" alt="ds5 7" src="https://github.com/user-attachments/assets/33ef97b3-2d6a-41d3-8611-0388b43513fb" />

```
height = [10, 24, 36, 40, 5]
names = ['one', 'two', 'three', 'four', 'five']
c1=['red', 'green'] 
c2=['b', 'g']
plt.bar (names, height, width=0.8, color=c1)
plt.xlabel('x - axis')
plt.ylabel('y - axis')
plt.title('My bar chart!')
plt.show()
```
<img width="844" height="544" alt="ds5 8" src="https://github.com/user-attachments/assets/eaae0bf4-69f9-4724-94e0-c31ba116feb6" />

```
 x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
 plt.hist(x, bins = 10, color='blue', alpha=0.5)
 plt.show()
```
<img width="861" height="505" alt="ds5 9" src="https://github.com/user-attachments/assets/57f8ac08-f8db-4140-aa08-dc22924a2878" />

```
 np.random.seed(0)
 data=np.random.normal(loc=0, scale=1, size=100)
 data
```
<img width="773" height="430" alt="ds5 10" src="https://github.com/user-attachments/assets/d5800092-f8c1-413d-882f-009e02b47089" />

```
 fig, ax= plt.subplots()
 ax.boxplot(data)
 ax.set_xlabel('Data')
 ax.set_ylabel('Values')
 ax.set_title('Box Plot')
```
<img width="793" height="569" alt="ds5 11" src="https://github.com/user-attachments/assets/4d4e9d1c-6ede-4cb6-8063-03ee131a2a9d" />

# Result:
 Include your result here
