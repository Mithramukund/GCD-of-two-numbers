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
```python
Program to find the gcd of two number using function.
Developed by: mithra mukundaa SG
RegisterNumber: 22005703
def gcd():
    a,b=int(input()),int(input())
    if a>b:
        min=a
    else:
        min=b
    for i in range(1,min+1):
        if a%i==0 and b%i==0:
            gcd=i
    print('GCD of two numbers is:',gcd)
*/
```

## Output:
![Screenshot (1)](https://user-images.githubusercontent.com/121608770/214827260-d327d9fa-a5f3-42f4-8c9f-5043298fb244.png)



## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
