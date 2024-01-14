First calc please give more advice PLEASE
current code:


def add(num1, num2):
    return num1 + num2

def subtract(num1, num2):
    return num1 - num2

def multiply(num1, num2):
    return num1 * num2

def divide(num1, num2):
    if num2 != 0:
        return num1 / num2
    else:
        print("Cannot divide by zero pluhga")

def display_menu():
    print("Please choose a pluh option")
    print("+")
    print("-")
    print("*")
    print("/")

while True:  
    display_menu()
    operator = input(":")
    num1 = float(input("First number: "))
    num2 = float(input("Next number: "))
    result = None
if operator == "+":
        result = add(num1, num2)
    elif operator == "-":
        result = subtract(num1, num2)
    elif operator == "*":
        result = multiply(num1, num2)
    elif operator == "/":
        result = divide(num1, num2)
    else:
        print("Invalid, you're not pluh, pick a right operation pluh pluh")

 if result is not None:
        print("The pluh result is:", result)
 choice = input("Press enter to continue or 'r' to quit... : ")
    if choice == 'r':
        break

    

