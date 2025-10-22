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
