# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Define a funtion
### Step 2:
Assign the list to a variable
### Step 3:
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5:
Print the values after circulation
### Step 6:
End the program

## Program:
~~~
def circulate():
    n=int(input())
    l=[10,20,30,40,50,60]
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
~~~

## Output:
![GitHub Logo](CIRCULATE.jpeg)

## Result:
PROGRAM FINISHED SUCCESSFULLY.
