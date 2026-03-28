# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **16** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `16` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program

#Add Code Here

a = 16

print(bin(a))
## Output
<img width="201" height="107" alt="image" src="https://github.com/user-attachments/assets/3f775773-d4d4-4593-8e33-33687f9dce12" />

## Result
Thus the program was successfully executed and obtained the result


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

#Add code Here

def result(a, b):

  print(a % b)

x = int(input("Enter the number 1:" ))

y = int(input("Enter the number 2:"))

result(x, y)
## Output
<img width="324" height="167" alt="image" src="https://github.com/user-attachments/assets/d41c1dbb-9f75-423c-96f7-902ad142d860" />

## Result
Thus the program was successfully executed and obtained the result.

# Lambda Function in Python: Addition of Two Numbers

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes two arguments `a` and `b`, and returns their sum.

## 🧠 Algorithm
1. Get two integer inputs from the user.
2. Use a **lambda function** to define a function `f` that returns `a + b`.
3. Call the function with the user inputs and print the result.

## 🧾 Program
#Add code here
a = int(input())
b = int(input())

f = lambda a, b: a + b
print(f(a, b))

## Output
<img width="302" height="163" alt="image" src="https://github.com/user-attachments/assets/bc20bdae-c598-49a5-82ed-f4c617ec9d71" />

## Result
Thus the program was successfully executed and obtained the result

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
#Add Code Here

n = int(input())

for i in range(n):
    
    for j in range(n - i - 1):
    
        print(" ", end="")
    
    num = 1
    
    for j in range(i + 1):
    
        print(num, end=" ")
        
        num = num * (i - j) // (j + 1)
    
    print()
## Sample Output
<img width="216" height="263" alt="image" src="https://github.com/user-attachments/assets/8dfb735a-e12a-40db-b61b-82eeb3d48ef9" />


## Result
Thus the program was successfully executed and obtained the result.


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
#Add code Here
num = int(input())

temp = num

rev = 0

while temp > 0:

    rev = (10 * rev) + temp % 10
    
    temp = temp // 10

if rev == num:
   
    print("Palindrome")

else:

    print("Not Palindrome")
## Output
<img width="286" height="135" alt="image" src="https://github.com/user-attachments/assets/acbeb975-ceb9-46a6-bea3-5ea148e517e5" />


## Result
Thus the program was successfully executed and obtained the result.
