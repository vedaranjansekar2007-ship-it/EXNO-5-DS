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
x = [1, 2, 3, 4, 5]
y = [3, 6, 2, 7, 1]
plt.plot(x,y)
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.show() 
```

<img width="1069" height="694" alt="Screenshot 2025-10-16 163533" src="https://github.com/user-attachments/assets/eca88bb8-a096-41d1-a777-a2539fe42227" /> 

```
x1 = [1,2,3]
y1 = [2,4,1]
x2 = [1,2,3]
y2 = [4,1,3]
plt.plot(x1,y1)
plt.plot(x2,y2)
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.show()
```

<img width="1116" height="699" alt="Screenshot 2025-10-16 163657" src="https://github.com/user-attachments/assets/5fdbbd1e-76c9-4094-b2d4-6e740dff9c3e" /> 

```
values = [5, 6, 3, 7, 2]
names  = ["A", "B", "C", "D", "E"]
plt.bar(values,names)
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.show() 
```

<img width="907" height="693" alt="Screenshot 2025-10-16 163818" src="https://github.com/user-attachments/assets/b72f9cfb-efc0-48f2-8f5b-4abb600a7146" /> 

```
x_values = [0,1,2,3,4,5]
y_values = [0,1,4,9,16,25] 
plt.scatter(x_values,y_values)
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.show()
```

<img width="905" height="683" alt="Screenshot 2025-10-16 163923" src="https://github.com/user-attachments/assets/ad369a0f-989a-4983-bef3-60db1288657c" /> 

```
activities = ['eat', 'sleep', 'work', 'play'] 
slices = [3, 7, 8, 6]
colors = ['r', 'y', 'g', 'b']
plt.pie(slices,labels=activities,colors=colors)
plt.show()  
```

<img width="792" height="621" alt="Screenshot 2025-10-16 164019" src="https://github.com/user-attachments/assets/ad17ed5c-dfad-4a47-9611-97b341e0ef07" />


```
import matplotlib.pyplot as plt
import numpy as np
labels = ['A', 'B']
values1 = [10, 15]
values2 = [12, 18]
c1 = ['red', 'green'] 
c2 = ['b', 'g']  
x = np.arange(len(labels))
width = 0.35  
fig, ax = plt.subplots()
bars1 = ax.bar(x - width/2, values1, width, label='Group 1', color=c1)
bars2 = ax.bar(x + width/2, values2, width, label='Group 2', color=c2)
ax.set_ylabel('Values')
ax.set_title('Bar Chart with Custom Colors')
ax.set_xticks(x)
ax.set_xticklabels(labels)
ax.legend()
plt.show()
```

<img width="897" height="758" alt="Screenshot 2025-10-16 164118" src="https://github.com/user-attachments/assets/379d31e7-5c7c-4008-8c3e-c2856e90c693" />


# Result:
 we performed data visualization using matplot python library
