# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: 
Get the two list forom the user
### Step 2: 
import the math module
### Step 3: 
Substitute the values in the distance formula  ![formula](/formula.jpg)
### Step 4: 
print the value useing the format function
### Step 5: 
Stop the program
### PROGRAM:
```
import math
d2=[10,6]
d1=[4,2]
distance=math.sqrt(((d2[0]-d1[0])**2)+((d2[1]-d1[1])**2))
print("{:.2f}".format(distance))
```

### OUTPUT:
![output](output.png)

### RESULT:
Thus the distance between two points obtained.
