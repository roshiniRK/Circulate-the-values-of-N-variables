# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:
Define a function circulate().
### Step 2: 
Get the value from the user for the list.
### Step 3: 
Get the value from the user for the number of rotation.
### Step 4: 
Using the slicing concept rotate the list.
### Step 5:
Print the result.

## Program:
```
#Program to circulate N values.
#Developed by: ROSHINI R K
#RegisterNumber:212222230123
def circulate():
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result)
```    

## Output:
![ex2output](https://user-images.githubusercontent.com/118956165/225949311-47b01168-0a0d-4515-ba67-2770e333da82.png)


## Result:
Thus,to write a python program to circulate the n variables using function concept is successfully executed.
