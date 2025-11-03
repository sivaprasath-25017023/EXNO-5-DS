# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY
### NAME : Sivaprasath R
### REGISTER NO : 25017023
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
### Line plot:
```
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
<img width="862" height="823" alt="Screenshot 2025-11-01 213728" src="https://github.com/user-attachments/assets/0c1608ed-5dc2-416c-b8e7-62c7d52f4696" />


### Scatter plot:

```
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
<img width="661" height="836" alt="Screenshot 2025-11-01 214015" src="https://github.com/user-attachments/assets/0a6669ba-404a-4367-9d51-3b37994f7d1a" />

### Pie chart:

```
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
<img width="609" height="785" alt="Screenshot 2025-11-01 214154" src="https://github.com/user-attachments/assets/c3099200-21bc-4703-8353-04374c4fa1c7" />

### Area chart:

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
<img width="651" height="408" alt="Screenshot 2025-11-01 214318" src="https://github.com/user-attachments/assets/56b90ff3-9aff-4921-ba7f-179980443a30" />

### Bar chart:

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
<img width="599" height="443" alt="Screenshot 2025-11-01 214459" src="https://github.com/user-attachments/assets/2aa25d5d-4b1d-4c75-ae4c-81775385270a" />

### Histogram:

```
x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x, bins = 10, color='blue', alpha=0.5)
plt.show()
```
<img width="556" height="402" alt="Screenshot 2025-11-01 214631" src="https://github.com/user-attachments/assets/68c8896f-ce9b-4abc-b6d7-f9bef8b68397" />

### Box Plot:

```
np.random.seed(0)
data=np.random.normal(loc=0, scale=1, size=100)
data
```
<img width="594" height="333" alt="Screenshot 2025-11-01 214949" src="https://github.com/user-attachments/assets/2f4ff008-de2d-4671-aec8-949dcde10510" />

```
fig, ax= plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')
```
<img width="603" height="481" alt="Screenshot 2025-11-01 215117" src="https://github.com/user-attachments/assets/ae43f6f6-c8a7-4c89-9fa6-9d10cba665f9" />







# Result:
 Thus, all the data visualization techniques of matplotlib has been implemented.
