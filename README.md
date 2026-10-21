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

for the activity this week. just incase the read me is not working.
https://colab.research.google.com/github/Gwynthx/Q2_FA1_Molave_Capate/blob/main/Copy_of_CS2_Capate_iterative_control_structures_.ipynb
    print("Division:", divide(num1, num2))
    
