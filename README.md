# python-basic-calculator
def calculator():
    print("Basic Calculator")
    num1 = float(input("Enter first number: "))
    num2 = float(input("Enter second number: "))
    print("Select operation:")
    print("1. Add")
    print("2. Subtract")
    print("3. Multiply")
    print("4. Divide")
    choice = input("Enter choice: ")
    if choice == "1":
        print("Result:", num1 + num2)
    elif choice == "2":
        print("Result:", num1 - num2)
    elif choice == "3":
        print("Result:", num1 * num2)
    elif choice == "4":
        print("Result:", num1 / num2)
    else:
        print("Invalid choice")
calculator()
Output :
Basic Calculator
Enter first number: 2
Enter second number: 3
Select operation:
1. Add
2. Subtract
3. Multiply
4. Divide
Enter choice: 1
Result: 5.0
=== Code Execution Successful ===
