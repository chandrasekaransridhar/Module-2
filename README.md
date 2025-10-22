## Sridhar (25017646)


# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program
```py
a=16
print(bin(a))
```


## Output
<img width="396" height="92" alt="image" src="https://github.com/user-attachments/assets/ce0b6b5b-e593-450c-8d0c-744d55c5a822" />

## Result
successfully wrote Python program to convert the number **16** into its **binary representation** using built-in Python functions.


# Functions in Python: Modulo Calculator

## 🎯 Aim
To write a Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.

## 🧠 Algorithm
1. Define a function called `result` that takes two arguments `a` and `b`.
2. Inside the function, compute the modulo using `a % b`.
3. Print the result of the modulo operation.
4. Get two integer inputs from the user.
5. Call the `result` function with the user-provided values.

## 🧾 Program
```py
def result(a,b):
    return a%b
a=int(input())
b=int(input())
c=result(a,b)
print(c)
```

## Output
<img width="1212" height="168" alt="image" src="https://github.com/user-attachments/assets/b2334647-4546-45a4-8465-ed88860cd78d" />

## Result
successfully wrote Python program that defines a function which accepts two values and returns their **modulo** using the `%` operator.


# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
```py
f=lambda a,b:a+b
a=int(input())
b=int(input())
print(f(a,b))
```

## Output
<img width="1123" height="162" alt="image" src="https://github.com/user-attachments/assets/a4ee8f38-7ce0-4d94-b8a7-341c3e293fdb" />

## Result
successfully wrote Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.


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



## Loops in Python: Palindrome Number Checker

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
```py
num=int(input())
temp=num
rev=0
while temp > 0:
    rev = (10 * rev) + temp % 10
    temp = temp // 10
if rev==num:
    print("this  is palindrome")
else:
    print("not palindrome")
```
## Output
<img width="1340" height="307" alt="Screenshot 2025-10-22 172234" src="https://github.com/user-attachments/assets/9bb88f0e-734a-4502-937b-ea8734f425d5" />
<img width="1584" height="347" alt="Screenshot 2025-10-22 172252" src="https://github.com/user-attachments/assets/91398bcb-9173-4ae6-bf60-8904a430cba7" />


## Result
successfully wrote Python program that checks whether a given number is a **palindrome** using loops.
