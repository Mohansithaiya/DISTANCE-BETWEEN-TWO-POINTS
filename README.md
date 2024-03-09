# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: 
From math module import sqrt function
### Step 2: 
Create a function definiton named dist()
### Step 3: 
Substitute the values in the distance formula  ![formula](/formula.JPG)
### Step 4: 
Print the result in float data type within the block
### Step 5: 
Assign values for the two points and Call the function header
### PROGRAM:
```python
import math
l1 = [4,2]
l2 = [10,6]
d = math.sqrt(((l2[0]-l1[0])**2)+((l2[1]-l1[1])**2))
print("{:.2f}".format(d))
```
  
### OUTPUT:
![Screenshot 2024-03-09 103925](https://github.com/Mohansithaiya/DISTANCE-BETWEEN-TWO-POINTS/assets/154211682/5c3095f7-c42a-465b-8b4b-935ee5d1db4e)


### RESULT:
Thus the distance the between two points is successfully executed
