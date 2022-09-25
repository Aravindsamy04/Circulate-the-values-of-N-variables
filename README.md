# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: define the function
### Step 2: Get input from the user
### Step 3: apply the formula
Get the value from the user for the number of rotation
### Step 4: print the output
Using the slicing concept rotate the list 
## Program:
```python
#Program to circulate N values.
#Developed by: Aravind samy
#RegisterNumber:22005040
def circulate():
    a=eval(input())
    n=int(input())
    a=a[n:]+a[:n]
    print("After circulating the values are:",a)
```

## Output:
![output](outputcirculate.png)

## Result:
Thus the circulate n variables are successfuly executed
