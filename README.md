# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program
```
x=16
y=bin(x)
print(y)
```

## Output
<img width="385" height="305" alt="517425138-a4806adc-6702-4908-a123-e3aa65423a1a" src="https://github.com/user-attachments/assets/7774c98f-8ce7-4ece-bc20-23f5a35f261e" />

## Result
Thus,the Python program to convert the number 16 into its binary representation using built-in Python functions is created successfully.


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
```
def result(a, b):
    modulo_value = a % b
    return modulo_value

a=int(input())
b=int(input())
print("modulo is", result(a, b))
```

## Output
<img width="675" height="329" alt="517425983-c2cf650f-4471-4a95-bbe3-c1905c3ef9b7" src="https://github.com/user-attachments/assets/84b296f9-c8ed-45da-a229-6696b1eb40ff" />

## Result
Thus,the Python program that defines a function which accepts two values and returns their modulo using the % operator is created successfully.


# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
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
<img width="499" height="384" alt="517426552-6b7c2f4e-b456-43b5-b2cf-1c7f3d347532" src="https://github.com/user-attachments/assets/fbf91713-3b38-44ea-b0c5-2ef032c37d40" />

## Result
Thus,the Python program that defines a lambda function which takes two arguments a and b, and returns their sum is created successfully.

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
```
rows = int(input())
coef = 1

for i in range(1, rows+1):
    for space in range(1, rows-i+1):
        print(" ",end="")
    for j in range(0, i):
        if j==0 or i==0:
            coef = 1
        else:
            coef = coef * (i - j)//j
        print(coef, end = " ")
    print()
```

## Sample Output
<img width="631" height="694" alt="517427138-d9d11500-0569-4dbb-9fdf-225df0786fcf" src="https://github.com/user-attachments/assets/b2e38e12-3989-469e-896b-23245e1732ce" />

## Result
Thus,the Python program that generates Pascal's Triangle using numbers. The number of rows is accepted from the user is created successfully.

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
<img width="776" height="193" alt="517427510-3a55a15f-3ac7-45fa-a389-c9655c2c8c30" src="https://github.com/user-attachments/assets/b9bc3918-ef56-46ab-8992-16a3a947fe17" />

## Result
Thus,the Python program that checks whether a given number is a palindrome using loops is created successfully.



## REVIEW PAGE FOR MODULE


<img width="1919" height="880" alt="image" src="https://github.com/user-attachments/assets/28b94de7-670b-4f1f-9e60-7ee704d68a6d" />

