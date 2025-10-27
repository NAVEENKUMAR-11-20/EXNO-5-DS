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
 Include the necessary coding and corresponding screenshots

 NAME   : NAVEEN KUMAR P
 REG NO : 212224240102

  ```python
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
marks=[13,45,63,78]
student=['ABC','QOR','EFB','TOB']
plt.plot(marks,student)
plt.xlabel('Marks')
plt.ylabel('Student name')
plt.show()
student=['A','B','C','D']
attendence=[90,85,73,88]
plt.plot(attendence,student)
plt.xlabel('Attendence')
plt.ylabel('Student name')
plt.show()
```
<img width="839" height="741" alt="image" src="https://github.com/user-attachments/assets/d53ebcbb-02f1-4f01-a30b-a6a7cc66074f" />

```python
x=[10,20,30,40,50]
y=[100,200,300,400,500]
plt.scatter(x,y,label='stars',color='green',marker='*',s=30)
plt.show()
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
<img width="746" height="751" alt="image" src="https://github.com/user-attachments/assets/d08cc40a-2696-44cb-8718-0dd3bc1d3832" />

```python
 act=['eat','sleep','work','play']
 slices=[3,7,8,6]
 color=['r','y','g','b']
 plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
 plt.legend()
 plt.show()
 feedback=['Good','excellent','Perfect','Ok']
 slices=[4,10,3,8]
 color=['y','r','b','g']
 plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
 plt.legend()
 plt.show()
```
<img width="785" height="721" alt="image" src="https://github.com/user-attachments/assets/7f088db4-89a0-4f17-8cdd-ffbc15abe9fd" />

```python
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
<img width="861" height="375" alt="image" src="https://github.com/user-attachments/assets/6eb67771-bc89-441b-8f78-fe564125bb98" />

```python
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
<img width="883" height="407" alt="image" src="https://github.com/user-attachments/assets/cbd2a00b-d364-43b4-9da8-eda99c55b57a" />

```python
 x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
 plt.hist(x, bins = 10, color='blue', alpha=0.5)
 plt.show()
```
<img width="734" height="383" alt="image" src="https://github.com/user-attachments/assets/d5694028-5d1a-4ad9-a4fe-4982dc97bd69" />

```python
 np.random.seed(0)
 data=np.random.normal(loc=0, scale=1, size=100)
 data
```
<img width="574" height="310" alt="image" src="https://github.com/user-attachments/assets/1c8d00dc-5d21-498b-9b72-486197ac9f3b" />

```python
 fig, ax= plt.subplots()
 ax.boxplot(data)
 ax.set_xlabel('Data')
 ax.set_ylabel('Values')
 ax.set_title('Box Plot')
```
<img width="663" height="471" alt="image" src="https://github.com/user-attachments/assets/0daf49ca-385b-4c30-94ff-a5129f58379c" />


# Result:
 Thus, all the data visualization techniques of matplotlib has been implemented
