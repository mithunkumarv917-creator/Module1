## Developed by: Mithun Kumar V (212225040236 / 25012629)

# 1.Conditional Statements in Python: Even or Odd Checker

## 🎯 Aim
To write a Python program to check whether the given number is **even** or **odd** using `if...else` statements.

## 🧠 Algorithm
1. Get an input from the user.
2. Convert the input to an integer and store it in a variable `a`.
3. Use the modulo operator `%` to check if `a % 2 == 0`.
   - If true, print `"EVEN"`.
   - Else, print `"ODD"`.
4. End the program.

## 🧾 Program
```
n = input()
a = int(input())

if a%2==0:
   print("EVEN")
else:
   print("ODD")
```
## Output
<img width="135" height="53" alt="image" src="https://github.com/user-attachments/assets/5a9c0482-e836-4865-9ae7-4240ed6e672f" /><br>
<img width="120" height="58" alt="image" src="https://github.com/user-attachments/assets/749af14f-4c62-45fb-8f5b-a70046fc8560" /><br>
## Result
Thus the program has been executed successfully.

# 2.Datatypes-Boolean Expression Evaluation in Python

## 🎯 Aim
To write a Python program that evaluates and prints the results of boolean and arithmetic expressions involving `True` and `False`.

## 🧠 Algorithm
1. Set variable `a` to the result of the expression `0 == True`.
2. Set variable `b` to the result of the expression `False == False`.
3. Set variable `c` to the result of the expression `True + True`.
4. Set variable `d` to the result of the expression `False + 9`.
5. Print the value of `a` with the label "a is".
6. Print the value of `b` with the label "b is".
7. Print the value of `c` with the label "c:".
8. Print the value of `d` with the label "d:".

## 💻 Program
```
a = 0 == True
b = False == False
c = True + True
d = False + 9

print("a is",a)
print("b is",b)
print("c:",c)
print("d:",d)
```

## Output
<img width="165" height="120" alt="image" src="https://github.com/user-attachments/assets/f7db982d-928c-4838-9255-936dd4f8adb2" />

## Result
Thus the program has been executed successfully.

# 3.Datatypes-Character Literal in Python

## 🎯 Aim
To write a Python program that prints the characters `'T'` and `'a'` using character literals.

## 🧠 Algorithm
1. Print the character `'T'`.
2. Print the character `'a'`.

## 🧾 Program
```
print('T')
print('a')
```

## Output
<img width="101" height="81" alt="image" src="https://github.com/user-attachments/assets/2d8ea888-3407-479e-a74f-1191cd811ba7" />

## Result
Thus the program has been executed successfully

# 4.🧮 Datatypes-Complex Number Creation in Python

## 🎯 Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

## 🧠 Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.

## 💻 Program
```
a = int(input())
b = int(input())

x = complex(a,b)

print(x)

print("Real part of x:",x.real)
print("Imaginary part of x:",x.imag)

```
## Output
<img width="354" height="154" alt="image" src="https://github.com/user-attachments/assets/737d28a9-a3c7-4aeb-8240-495d3af9076d" />

## Result
Thus the program has been executed successfully.

# 5.Datatypes-Read and Print a String in Python

## 🎯 Aim
To write a Python program to read a string from the user and then print it.

## 🧠 Algorithm
1. Assign a variable named `men_stepped_on_the_moon`.
2. Use `input()` to read a string from the user and store it in the variable.
3. Print the value stored in the variable.

## 🧾 Program
```
men_stepped_on_the_moon = input()

print("Printing whatever stored:",men_stepped_on_the_moon)
```
## Output
<img width="526" height="74" alt="image" src="https://github.com/user-attachments/assets/bd921a40-37ce-4e93-990e-e2852cda2285" />

## Result
Thus the program has been executed successfully.
