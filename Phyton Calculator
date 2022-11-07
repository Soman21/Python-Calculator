# Simple calculator that can add, subtract, multiply and divide using functions written in Python Language
# Nwachukwu Maryann Mmesoma 2017364085

# This function adds two numbers
def add(num1, num2):
    return num1 + num2

# This function subtracts two numbers
def subtract(num1, num2):
    return num1 - num2

# This function multiplies two numbers
def multiply(num1, num2):
    return num1 * num2

# This function divides two numbers
def divide(num1, num2):
    return num1 / num2

print("Select operation -\n"\
"1. Addition\n"\
"2. Subtraction\n"\
"3. Multiplication\n"\
"4. Divison\n")


while True:
    # take input from the user
    choice = input("Select operations 1, 2, 3, 4: ")

    # check if choice is one of the four options
    if choice in ('1', '2', '3', '4'):
        num1 = float(input("Enter first number: "))
        num2 = float(input("Enter second number: "))

        if choice == '1':
            print(num1, "+", num2, "=", add(num1, num2))

        elif choice == '2':
            print(num1, "-", num2, "=", subtract(num1, num2))

        elif choice == '3':
            print(num1, "*", num2, "=", multiply(num1, num2))

        elif choice == '4':
            print(num1, "/", num2, "=", divide(num1, num2))
        
        # check if the user wants another calculation
        # break the while loop if the answer is n
        next_calculation = input("Let's do next calculation? (y/n): ")
        if next_calculation == "no":
          break
    
    else:
        print("Invalid Input")
