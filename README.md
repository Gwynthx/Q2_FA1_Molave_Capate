# Creating a Modular Mini-Program #
def add_numbers(num1, num2):
    return num1 + num2

def subtract_numbers(num1, num2):
    return num1 - num2

def multiply_numbers(num1, num2):
    return num1 * num2

def divide_numbers(num1, num2):
    if num2 == 0:
        return None
    return num1 / num2

num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))

print("Sum:", add(num1, num2))
print("Difference:", subtract(num1, num2))
print("Product:", multiply(num1, num2))

if num2 == 0:
    print("Division: Cannot divide by zero")
else:
    print("Division:", divide(num1, num2))
    
