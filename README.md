# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance between two 2 points
## ALGORITHM:
### Step 1: 
import math module to perform sqrt function.
### Step 2: 
Assign the values for the coordinates x1,x2,y1,y2 as given in the question.
### Step 3: 
Substitute the values in the distance formula  ![formula](/formula.JPG)
### Step 4: 
This substitution is given within the sqrt function .
### Step 5:
Using round function 2 decimal point precision is achieved.
### Step 6:
Use print function to get the appropriate output. 
### PROGRAM:
```
#Program to find the distance between two points.
#Developed by: U KRITHIGA
#RegisterNumber:23006499
import math
x1=4;x2=10;y1=2;y2=6
print(round(math.sqrt(((x2-x1)**2)+((y2-y1)**2)),2))
```
### OUTPUT:
![Alt text](<Distance ss.png>)
### RESULT:
The distance between two 2 points is calculated !!
