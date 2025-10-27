
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
 ## Coding and Output:
 ```
NAME : VIGNESH G
REGISTER NO : 212224230301
```


```py
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
```

### Line Plot:

```py
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
<img width="500" height="400" alt="Screenshot 2025-10-27 102608" src="https://github.com/user-attachments/assets/69833bea-a816-4eb3-a599-0c974d697a41" width="300" height="300" />
<img width="500" height="400" alt="Screenshot 2025-10-27 102601" src="https://github.com/user-attachments/assets/d065aafd-6d99-41a1-9c4c-064afe699e3a" width="300" height="300" />



### Scatter Plot:

```py
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
<img width="500" height="400" alt="Screenshot 2025-10-27 102616" src="https://github.com/user-attachments/assets/9254cd46-73f7-477d-bf32-6287a6fdfece" width="300" height="300" />

<img width="500" height="400" alt="Screenshot 2025-10-27 103122" src="https://github.com/user-attachments/assets/40172796-b7ac-4844-8ca1-4634d1290d87" width="300" height="300" />"300">


### Pie Chart:

```py
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

<img width="500" height="400" alt="Screenshot 2025-10-27 102642" src="https://github.com/user-attachments/assets/d7c06a0d-012b-43e9-9b90-8743118ab2fb" width="300" height="300" />
<img width="500" height="400" alt="Screenshot 2025-10-27 102636" src="https://github.com/user-attachments/assets/76338339-5546-4ed9-ba4f-7940e8e64346" width="300" height="300" />




### Area Chart:

```py
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


<img width="500" height="400" alt="Screenshot 2025-10-27 102647" src="https://github.com/user-attachments/assets/00d26420-7293-4c8d-9520-fb3eb970785b" width="300" height="300" />


### Bar Chart:

```py
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

<img width="500" height="400" alt="Screenshot 2025-10-27 102652" src="https://github.com/user-attachments/assets/1f801766-25cd-4b38-b82c-0811706e7166" width="300" height="300" />



### Histogram:

```py
x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x, bins = 10, color='blue', alpha=0.5)
plt.show()
```

<img width="500" height="400" alt="Screenshot 2025-10-27 102657" src="https://github.com/user-attachments/assets/037f60a6-3e67-4a84-8605-58083000e49d" width="300" height="300" >




### Box Plot:

```py
np.random.seed(0)
data=np.random.normal(loc=0, scale=1, size=100)
data

```

<img width="500" height="400" alt="Screenshot 2025-10-27 103345" src="https://github.com/user-attachments/assets/693d9bab-0a2e-4e9f-9819-2b795e059d2c" width="300" height="300" />



```py
fig, ax= plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')
```

<img width="500" height="400" alt="Screenshot 2025-10-27 103452" src="https://github.com/user-attachments/assets/d6b4c998-5a8c-4890-b2ef-50b85f1a9bb1" width="300" height="300" />



# Result:
Thus, all the data visualization techniques of matplotlib has been implemented.
