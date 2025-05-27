# Ex-01- Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **76** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `76` to a variable `x`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program
```
x=76
y=bin(x)
print(y)
```

## Output
![Screenshot 2025-05-15 033710](https://github.com/user-attachments/assets/291407f9-b9b0-4057-9594-3f2b0e77ad8d)

## Result
Thus the program to convert the number **76** into its **binary representation** using built-in Python functions has executed successfully.


# Ex-02-Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program
```
def result(a,b):
    mod=a%b
    
    print(f"modulo is {mod}")

a = int(input())
b = int(input())

result(a,b)
```

## Output
![Screenshot 2025-05-15 035321](https://github.com/user-attachments/assets/dff9e1c3-c9a1-474f-bf9e-7b2ee9017170)

## Result
Thus the program that defines a function which accepts two values and returns their **modulo** using the `%` operator has been executed successfully.


# Ex-03-Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a`, `b` and `c`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b + c`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
```
i=int(input())
j=int(input())
z=int(input())

f = lambda a, b,c: a+b+c

print(f(i, j,z))
```

## Output
![Screenshot 2025-05-15 040119](https://github.com/user-attachments/assets/327fb6c6-77e8-46c3-969e-5508d57979b7)

## Result
Thus the program that defines a **lambda function** which takes two arguments `a`, `b` and `c`, and returns their sum has executed successfully.


# 🔺Ex-04 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
```
rows = int(input())
coef = 1
for i in range (1, rows+1):
    for space in range (1, rows-i+1):
        print(" ",end="")
    for j in range(0, i):
        if j==0 or i==0:
            coef = 1
        else:
            coef = coef * (i - j)//j
        print(coef, end= " ")
    print()
```
## Output
![Screenshot 2025-05-15 042808](https://github.com/user-attachments/assets/e8a9d847-2523-4fe1-9eab-b0f963f73ecb)

## Result
Thus the program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user has been executed successfully.


## Ex-05- Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
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
![Screenshot 2025-05-15 043438](https://github.com/user-attachments/assets/3a1d9692-79b6-4c9b-97d1-6c10e735b3d6)

## Result
Thus the program that checks whether a given number is a **palindrome** using loops has been executed successfully.
