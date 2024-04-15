# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: 
Define the coordinates of the two points.

### Step 2: 
Calculate the differences between the x-coordinates and y-coordinates of the two points.

### Step 3: 
Substitute the values in the distance formula  ![formula](/formula.JPG)

### Step 4:
Square the differences and add them. 

### Step 5:
Take the square root of the sum to find the distance between the two points.

### PROGRAM:
```
#Program to find the distance between two points
#Developed By:Priyadharshan S
#Reference No.: 212223240127
import numpy as np
l1=[4,2]
l2=[10,6]
dist=np.sqrt((l2[0]-l1[0])**2+(l2[1]-l1[1])**2)
print("{:.2f}".format(dist))
```

### OUTPUT:

![image](https://github.com/S-Priyadharshan/DISTANCE-BETWEEN-TWO-POINTS/assets/145854138/aa17ab93-a4e2-4324-97c3-8a8b2eb14263)


### RESULT:
Thus the program is successfully compiled.
