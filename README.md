def factorial(n):
    if n == 0 or n == 1:
        return 1
    else:
        return n * factorial(n-1)

number = int(input("Enter a number: "))  # Prompt the user for a number
result = factorial(number)  # Calculate the factorial

print("The factorial of", number, "is", result)
