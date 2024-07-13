# calculate
# Function to calculate the factorial of a number
def factorial(n):
    if n == 0:
        return 1
    else:
        result = 1
        for i in range(1, n + 1):
            result *= i
        return result

# Ask the user for a number
user_number = int(input("Enter a number: "))

# Calculate the factorial
fact = factorial(user_number)

# Print the factorial
print(f"The factorial of {user_number} is: {fact}")
