# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number *16* into its *binary representation* using built-in Python functions.

## 🧠 Algorithm
1. Assign the value 16 to a variable a.
2. Use the built-in bin() function to convert the number to binary.
3. Print the result.

## 🧾 Program


x=16
y=bin(x)
print(y)

## Output
![image](https://github.com/user-attachments/assets/2e985875-d209-49d9-ad9e-5bb5b133ae3b)

## Result
Thus,the Python program to convert the number 16 into its binary representation using built-in Python functions is created successfully.

# Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their *modulo* using the % operator.

## 🧠 Algorithm
1. Define a function called result that takes two arguments a and b.
2. Inside the function, compute the modulo using a % b.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the result function with the user-provided values.

## 🧾 Program


def result(a, b):
    modulo_value = a % b
    return modulo_value

a=int(input())
b=int(input())
print("modulo is", result(a, b))

## Output
![image](https://github.com/user-attachments/assets/c7fade8a-0d6a-4138-b796-cf2f2d7398ba)

## Result
Thus,the Python program that defines a function which accepts two values and returns their modulo using the % operator is created successfully.
# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a *lambda function* which takes two arguments a and b, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a *lambda function* to define a function f that returns a + b.
3. Call the function with the user inputs and print the result.

## 🧾 Program

i=int(input())
j=int(input())
z=int(input())

f = lambda a, b,c: a+b+c

print(f(i, j,z))

## Output
![image](https://github.com/user-attachments/assets/ebd5beac-5f4f-4be7-beac-8e0f9dac5ec8)

## Result
Thus,the Python program that defines a lambda function which takes two arguments a and b, and returns their sum is created successfully.

# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate *Pascal’s Triangle*, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates *Pascal's Triangle* using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program

rows = int(input())
coef = 1

for i in range(1, rows+1):
    for space in range(1, rows-i+1):
        print(" ",end="")
    for j in range(0, i):
        if j==0 or i==0:
            coef = 1
        else:
            coef = coef * (i - j)//j
        print(coef, end = " ")
    print()

## Sample Output
![image](https://github.com/user-attachments/assets/f852768f-ddf9-4977-8f28-11abd2af690a)

## Result
Thus,the Python program that generates Pascal's Triangle using numbers. The number of rows is accepted from the user is created successfully.

## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a *palindrome* using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable num.
2. Assign the value of num to a temporary variable temp.
3. Initialize a variable rev to 0 (used to store the reversed number).
4. Use a while loop to reverse the digits:
   - While temp > 0:
     - rev = (10 * rev) + temp % 10
     - temp = temp // 10
5. After the loop, compare rev with num:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program

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

## Output
![image](https://github.com/user-attachments/assets/f5719231-1cc7-443a-9942-d40ff7ec1748)

## Result
Thus,the Python program that checks whether a given number is a palindrome using loops is created successfully.
