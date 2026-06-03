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
~~~
n = int(input())

for i in range(n):
    num = 1
    for j in range(i + 1):
        print(num, end=" ")
        num = num * (i - j) // (j + 1)
    print()
~~~

## Sample Output
<img width="500" height="532" alt="{DE6FC07D-142D-49A0-BE2A-3F138C109C52}" src="https://github.com/user-attachments/assets/5a073594-ffd9-4253-90fd-e5aa8fc1ca50" />


## Result
Thus, the Python program to generate Pascal's Triangle using numbers for the given number of rows was executed successfully.
