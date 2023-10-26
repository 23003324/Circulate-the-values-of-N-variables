# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Define the function for the program.
### Step 2: 
Get the inputs from the user.
### Step 3: 
Get the value from the user for the number of rotation.
### Step 4: 
Using the slicing concept rotate the list.

### Step 5: 
Print the values after circulating the variable.
### Step 6: 
End the program.
## Program:
```#Program to circulate N values.
#Developed by: HARITHA RAMESH
#RegisterNumber:23003324
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are: {}".format(l))
```
## Output:

![Alt text](<n variable.png>)



## Result:
Thus the circulating the N-variable are successfully executed.
