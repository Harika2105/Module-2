## Built-in Functions -Binary Conversion Using Built-in Functions in Python
## Aim
To write a Python program to convert the number 16 into its binary representation using built-in Python functions.

## Algorithm
1. Assign the value 16 to a variable a.
2. Use the built-in bin() function to convert the number to binary.
3. Print the result.
## Program
```
a=16 
print(bin(a)
```
## Output
<img width="777" height="356" alt="569651764-4f830648-3a32-413c-a6ff-db99cd9b09cd" src="https://github.com/user-attachments/assets/e3be4fdc-3bd5-48e3-a218-6bfa35b0e010" />

## Result
Thus, the program has been successfully executed.


## Functions in Python: Modulo Calculator
## Aim
To write a Python program that defines a function which accepts two values and returns their modulo using the % operator.

## Algorithm
1. Define a function called result that takes two arguments a and b.
2. Inside the function, compute the modulo using a % b.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the result function with the user-provided values.
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
<img width="918" height="429" alt="569654329-64167eba-18ee-4c7f-b2b8-fcd803ee1291" src="https://github.com/user-attachments/assets/4adc6d6b-d105-4c05-a060-2712ae95210e" />

## Result
The program to return two values modulo is successful.

## Lambda Function in Python: Addition of Two Numbers
## Aim
To write a Python program that defines a lambda function which takes two arguments a and b, and returns their sum.

## Algorithm
1. Get two integer inputs from the user.
2. Use a lambda function to define a function f that returns a + b.
3. Call the function with the user inputs and print the result.
## Program
```
a=int(input()) 
b=int(input()) 
f=lambda a,b: a+b 
print(f(a,b))
```
## Output
<img width="644" height="265" alt="569655382-81ec9809-d969-42bb-9bba-23bef00107d9" src="https://github.com/user-attachments/assets/8ca43d4c-fca5-4ff7-9a49-8c1b6254bb2e" />

## Result
Thus, the program has been successfully executed.

## 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python
This project demonstrates a simple Python program to generate Pascal’s Triangle, where the number of rows is provided by the user.

## Aim
To write a Python program that generates Pascal's Triangle using numbers. The number of rows is accepted from the user.

## Algorithm
1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
Print appropriate spaces to shape the triangle.
## Compute values using the formula:
[ C(n, k) = \frac{n!}{k!(n-k)!} ]
Print all rows of Pascal’s Triangle.
End the program.
## Program
```
def factorial(n):
    if n == 0 or n == 1:
        return 1
    return n * factorial(n - 1)

def combination(n, k):
    return factorial(n) // (factorial(k) * factorial(n - k))

num_rows = int(input("Enter number of rows: "))

for i in range(num_rows):
    print(' ' * (num_rows - i - 1), end='')
    for j in range(i + 1):
        print(combination(i, j), end=' ')
    print()
```
## Sample Output
<img width="290" height="324" alt="569656336-8d3c46fd-bcff-4281-aca3-5db74c40fb7a" src="https://github.com/user-attachments/assets/d4ecb80a-9e09-49b1-9b70-47cdc86d218d" />

## Result
Thus, the program has been successfully executed.

## Loops in Python: Palindrome Number Checker
## Aim
To write a Python program that checks whether a given number is a palindrome using loops.

## Algorithm
1. Get input from the user and assign it to a variable num.
2. Assign the value of num to a temporary variable temp.
3. Initialize a variable rev to 0 (used to store the reversed number).
4. Use a while loop to reverse the digits:
While temp > 0:
rev = (10 * rev) + temp % 10
temp = temp // 10
5. After the loop, compare rev with num:
If equal, print that the number is a palindrome.
Else, print that it is not a palindrome.
## Program
```
num=int(input()) 
rev=0 
temp=num 
while temp>0: 
    rev=(10*rev)+temp%10 
    temp//=10 
    if rev==num: 
        print("The given number {} is a Palindrome".format(num)) 
    else:
        print("The given number {} is not a palindrome".format(num))
```
## Output
<img width="834" height="158" alt="569658066-be652eb2-140e-477d-a8a8-97ff35ab8b04" src="https://github.com/user-attachments/assets/0ddcc842-2f61-47fd-8d04-a4ea09d08c43" />

## Result
Thus, the program has been successfully executed .
