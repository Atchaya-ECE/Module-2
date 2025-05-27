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
