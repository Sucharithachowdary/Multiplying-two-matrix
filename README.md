# Multiplying-two-matrix

## AIM:
To write a python program to multiply two arrays using numpy

## ALGORITHM:

### Step 1:
Import numpy as np
### Step 2:
declare a variable array1 as a empty list
### Step 3:
declare a variable array2 as a empty list
### Step 4:
get input value as n
### Step 5:
iterate a variable i in range n by for loop and append the values to the list array 1 end the loop
### Step 6:
iterate a variable j in range n by for loop and append the values to the list array 2 end the loop
### Step 7:
Declare a variable product to array and compute array1*array2
### Step 8:
Print the value of the product

## PROGRAM: 
import numpy as np
l1,l2=[],[]
n=int(input())
for i in range(n):
    l1.append(int(input()))
for i in range(n):
    l2.append(int(input()))
array_1=np.array(l1)
array_2=np.array(l2)
product=array_1*array_2
print("Product of two arrays is:",product)
## OUTPUT:
![j1](https://user-images.githubusercontent.com/94166007/153748269-36dff8fb-ddee-4859-ad65-3e5ab41e938f.PNG)

## RESULT:
Thus the program runs successfully
