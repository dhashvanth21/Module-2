
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
![image](https://github.com/user-attachments/assets/891415de-65f4-460a-964e-041290762893)


## Result
Thus,the Python program that defines a lambda function which takes two arguments a , b and c, and returns their sum is created successfully.


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

![image](https://github.com/user-attachments/assets/bc626379-520f-4d7d-9224-2de809f8c12c)


## Result
Thus,the Python program that defines a function which accepts two values and returns their modulo using the % operator is created successfully.
