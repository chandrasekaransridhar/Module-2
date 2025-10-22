# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

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
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
```py
import math
rows=int(input())
for n in range(rows):
        print(" " * (rows - n), end=" ")
        for k in range(n + 1):
            value = math.comb(n, k)
            print(value, end=" ")
        print()
```

## Sample Output
<img width="1371" height="355" alt="image" src="https://github.com/user-attachments/assets/a3885655-0d33-40cf-b204-19fbfc5932ef" />

## Result
successfully Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.
