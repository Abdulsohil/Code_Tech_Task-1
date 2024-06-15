def calculator():
    # Prompt user to enter two numbers
    number_1 = float(input("Enter the first number: "))
    number_2 = float(input("Enter the second number: "))

    # Prompt user to choose an operation
    print("Choose an operation:")
    print("1. Add")
    print("2. Subtract")
    print("3. Multiply")
    print("4. Divide")

    operation = input("Enter the operation number (1/2/3/4): ")

    # Perform the selected operation
    if operation == '1':
        result = number_1 + number_2
        print("The result is:", result)

    elif operation == '2':
        result = number_1 - number_2
        print("The result is:", result)

    elif operation == '3':
        result = number_1 * number_2
        print("The result is:", result)

    elif operation == '4':
        if number_2 == 0:
            print("Cannot divide by zero.")
        else:
            result = number_1 / number_2
            print("The result is:", result)

    else:
        print("Invalid operation. Please try again.")

# Call the calculator function
calculator()
