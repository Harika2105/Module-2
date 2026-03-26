# Functions in Python: Modulo Calculator

## Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## Program
```
def result(a, b):
    modulo_value = a % b
    return modulo_value

a=int(input())
b=int(input())
print("modulo is", result(a, b))
```

## Output
<img width="918" height="429" alt="Screenshot 2026-03-26 154712" src="https://github.com/user-attachments/assets/64167eba-18ee-4c7f-b2b8-fcd803ee1291" />

## Result
The program to return two values modulo is successful.
