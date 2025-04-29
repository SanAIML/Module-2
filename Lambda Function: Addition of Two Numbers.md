# Lambda Function in Python: Calculate the value of the following expression by using lambda function

## 🎯 Aim
To write a Python program that defines a **lambda function** which takes three arguments `a` ,`b`, and `c` and returns their sum.

## 🧠 Algorithm
1)Start the program.

2)Input three integers from the user: `x`, `y`, and `z`.

3)Add `10` to `x`, and add `2` to `y`.

4)Multiply the result of `(y + 2)` with `z`.

5)Add that product to `(x + 10)` and display the final result.

## 🧾 Program
```
calculate_expression = lambda x, y, z: (x + 10) + (y + 2) * z

# Input values from the user
x = int(input())
y = int(input())
z = int(input())

# Calculate and display the result
result = calculate_expression(x, y, z)
print(result)
```



## Output
![Screenshot 2025-04-29 111253](https://github.com/user-attachments/assets/9fa3654e-d606-4028-bde4-84860f843e8e)


## Result
The Expected output is acheived
