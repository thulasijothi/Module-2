## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome**.

## 🧠 Algorithm
1.Start the program.
2.Read a number from the user.
3.Store the original number in a temporary variable for later comparison.
4.Reverse the digits of the number:
   Initialize a variable (reverse) to 0.
   Use a loop:
       Get the last digit of the number using % 10.
       Multiply reverse by 10 and add the last digit.
       Remove the last digit from the number by doing integer division // 10.
5.Compare the reversed number with the original number:
    If they are the same, it is a palindrome.
    Otherwise, it is not a palindrome.
6.Print the result.
7.End the program.

## 🧾 Program
num=input()
rev=num[::-1]
if num==rev:
    print(f"The given number {num} is a Palindrome")
else:
    print(f"The given number {num} is not a palindrome")
    
## Output
![image](https://github.com/user-attachments/assets/97b866d8-5c71-424c-8ceb-4f3ec408e6ef)

## Result
This program that checks whether a given number is a **palindrome** is successfully executed.
