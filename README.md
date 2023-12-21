# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
```python

Program to find the square root for the given number(newton's method) using function.
Developed by: Swaminathan V
RegisterNumber: 23000747
def sqroot():
    num1=int(input())
    num2=int(float(num1))
    for i in range(100):
        num1=0.5*(num1+num2/num1)
    print("Square root of the number:",num1)
sqroot()

```

## Output:
![Square root of two numbers](https://github.com/SwaminathanV23000747/Square-root-of-a-number/assets/148931113/2bb8a550-e93c-4d8f-90e7-e98274405ae7)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
