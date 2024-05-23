
```python
# Function to add two numbers
def add(x, y):
    return x + y

# Function to subtract two numbers
def subtract(x, y):
    return x - y

# Function to multiply two numbers
def multiply(x, y):
    return x * y

# Function to divide two numbers
def divide(x, y):
    if y == 0:
        return "Cannot divide by zero"
    return x / y

print("Welcome to the Basic Calculator!")
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))

print("Select operation:")
print("1. Addition")
print("2. Subtraction")
print("3. Multiplication")
print("4. Division")

choice = input("Enter your choice (1/2/3/4): ")

if choice == '1':
    print("Result: ", add(num1, num2))
elif choice == '2':
    print("Result: ", subtract(num1, num2))
elif choice == '3':
    print("Result: ", multiply(num1, num2))
elif choice == '4':
    print("Result: ", divide(num1, num2))
else:
    print("Invalid input. Please choose a valid operation.")
