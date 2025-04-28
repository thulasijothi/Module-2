# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim
Write a Python Program to print pyramid pattern of numbers .Get the input for the number of rows.

## 🧠 Algorithm
1.Start the program.
2.Read the number of rows from the user.
3.Use a for loop to iterate through each row (from 1 to the given number of rows).
4.For each row:
    Print spaces to center-align the pyramid.
    Print numbers increasing from 1 up to the current row number.
5.Move to the next line after each row is printed.
6.End the program.

## 🧪 Program
rows = int(input())
for i in range(1, rows + 1):
    for j in range(1, i + 1):
        print(j, end=' ')
    print('')

## Sample Output:
![image](https://github.com/user-attachments/assets/1d9e3888-f0a6-4fb6-b183-f0685058c3a0)

## Result
This Program to print pyramid pattern of numbers & Get the input for the number of rows is successfully executed.

