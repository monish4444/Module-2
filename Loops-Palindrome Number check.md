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
~~~
num=int(input())
rev=0
temp=num

while temp>0:
    dig=temp%10
    rev=(rev*10)+dig
    temp=temp//10
    
if num==rev:
    print(f"The given number {num} is a Palindrome")
        
else:
    print(f"The given number {num} is not a palindrome")
~~~
## Output
<img width="1131" height="250" alt="image" src="https://github.com/user-attachments/assets/9fc699bb-5f81-43bd-a37a-a45cd6611ee6" />


## Result
Thus, the Python program to check whether a given number is a palindrome using loops was executed successfully.
