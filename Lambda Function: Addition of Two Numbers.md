# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
Write a program in Python to calculate the value of the following expression by using lambda function.
The expression is -
(x + 10) + (y + 2) * z

## 🧠 Algorithm
1.Start the program.
2.Read the values of x, y, and z from the user.
3.Define a lambda function that calculates the value of the expression:
        (x+10)+(y+2)×z
4.Call the lambda function by passing x, y, and z as arguments.
5.Print the result.
6.End the program.

## 🧾 Program
x = int(input())
y = int(input())
z = int(input())

expr = lambda x, y, z: (x + 10) + (y + 2) * z
print(expr(x, y, z))

## Output
![image](https://github.com/user-attachments/assets/2535f7aa-5429-44ba-aae0-9b4d5933ff7f)


## Result
This program to calculate the value of the following expression by using lambda function is successfully executed.
