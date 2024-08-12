# Python sample pgm-CSI 

# Define a function to perform basic mathematical operations
def basic_operations(a, b):
    # Addition
    addition = a + b
    # Subtraction
    subtraction = a - b
    # Multiplication
    multiplication = a * b
    # Division
    # Check to avoid division by zero
    if b != 0:
        division = a / b
    else:
        division = "undefined (division by zero)"
    
    return addition, subtraction, multiplication, division

# Example usage
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))

add, sub, mul, div = basic_operations(num1, num2)

print(f"Addition: {num1} + {num2} = {add}")
print(f"Subtraction: {num1} - {num2} = {sub}")
print(f"Multiplication: {num1} * {num2} = {mul}")
print(f"Division: {num1} / {num2} = {div}")
