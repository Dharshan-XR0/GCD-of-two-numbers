# Find the GCD of two numbers

## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
```
Program to find the gcd of two number using function.
Developed by: V.DHARSHAN
RegisterNumber: 22003103

def gcd():
    n1=int(input())
    n2=int(input())
    if n1>n2:
        smaller=n2
    else:
        smaller=n1
    for i in range(1, smaller+1):
        if(n1%i==0 and n2%i==0):
           gcd1=i
    print("GCD of two numbers is:",gcd1) 
 ```

## Output:


![image](https://user-images.githubusercontent.com/113497491/191740037-a89a6aab-2588-4a64-898c-8588d9dd7428.png)



## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
