## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Start the program.
### Step 2: 
Get the input from the user using eval(input())
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
using concatination operation display in the entire rotated list
### Step 6: 
Stop the program
## Program:
```
#Program to circulate N values.
#Developed by:Franklin raj g 
#RegisterNumber:23001518
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n: ]+l[ :n]
    print("After circulating the values are:",l)
 ```     
                 
## Output:!
![circulate](https://github.com/franklinraj/Circulate-the-values-of-N-variables/assets/148993740/1bd31c2b-f100-4904-a2ab-61691b405a77)

## Result:
Thus the python program for Circulate the values of a variables is executed successfully.
