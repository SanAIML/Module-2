# Built-in Functions -Binary Conversion Using Built-in Functions in Python

## 🎯 Aim
To write a Python program to convert the number **25** into its **binary representation** using built-in Python functions.

## 🧠 Algorithm
1. Assign the value `25` to a variable `a`.
2. Use the built-in `bin()` function to convert the number to binary.
3. Print the result.

## 🧾 Program
```
def decimal_to_binary(decimal_number):
    
    binary_number = bin(decimal_number)[2:]
    return binary_number

# Input from the user
decimal_number = int(input())

# Convert and display the binary equivalent
binary_number = decimal_to_binary(decimal_number)
print(f"0b{binary_number}")


```



## Output
![Screenshot 2025-04-29 105810](https://github.com/user-attachments/assets/dd3f4527-1466-416f-a236-370dfac5c76f)


## Result
The expected Output is acheived 
