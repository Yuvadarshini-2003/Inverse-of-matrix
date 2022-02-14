# Inverse-of-matrix

## AIM:
To write a program to perform Inverse-of-matrix using python programming.

## ALGORITHM:
### Step 1:
Import Numpy module as np.

### Step 2:
Create empty lists.

### Step 3:
Get input from the user for number of rows and columns.

### Step 4:
Use nested lists to append list.

### Step 5:
Print the inverse of the array using np.linalg.inv .

## PROGRAM:
~~~
import numpy as np
la=[]
lb=[]
n1=int(input())
n2=int(input())
for i in range(n1):
    for j in range(n2):
        val=int(input())
        la.append(val)
    lb.append(la)
    la=[]
print(lb)
inverse=np.linalg.inv(lb)
print(inverse)
~~~
## OUTPUT:
![inverse](inv.jpg)
## RESULT:
Thus the program is written to perform Inverse-of-matrix using python programming.