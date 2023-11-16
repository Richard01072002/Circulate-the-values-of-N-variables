# EXP-2 Circulate-the-values-of-N-variables
## Date: 18.08.2023
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: Get the values from the user
### Step 2: Assign the value of variable to a temporary variable
### Step 3: Get the value from the user for the number of rotation
### Step 4:Using the slicing concept rotate the list
### Step 5: Print both the values it would be interchanged
### Step 6: End the program
## Program:

```
#Program to circulate N values.
#Developed by:Richardson A
#RegisterNumber:23000803

def circulate():
    l=eval(input())
    n=int(input())
    l=l[n: ]+l[ :n]
    print("After circulating the values are:",l)
```


## Output:

<img width="1440" alt="Screenshot 2023-09-17 at 11 36 25 AM" src="https://github.com/Richard01072002/Circulate-the-values-of-N-variables/assets/141472248/a9b40703-fad9-4f9f-b62a-86fffe4a0994">


## Result:


