# python-assignment-1
def calculator():
    # Define numbers and operation
    num1 = 7.5
    num2 = 3.2
    operation = '+'  # Change this to '-', '*', or '/' as needed

    # Perform the operation
    if operation == '+':
        result = 7.5 + 3.2
        print(f"7.5 + 3.2 = {result}")
    elif operation == '-':
        result = 7.5 - 3.2
        print(f"7.5 - 3.2 = {result}")
    elif operation == '*':
        result = 7.5 * 3.2
        print(f"7.5 * 3.2 = {result}")
    elif operation == '/':
        if 3.2 != 0:
            result = 7.5 / 3.2
            print(f"7.5 / 3.2 = {result}")
        else:
            print("Error: Division by zero is not allowed.")
    else:
        print("Invalid operation. Please enter +, -, *, or /.")

# Run the calculator function
calculator()
