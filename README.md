🎉 Fun Calculator 🎉
Welcome to the Fun Calculator! This simple Python program lets you perform basic arithmetic operations (addition, subtraction, multiplication, and division) on two numbers. It’s easy, quick, and fun! 😎

Features
Add two numbers ➕

Subtract two numbers ➖

Multiply two numbers ✖️

Divide two numbers ➗ (with a basic safeguard for division by zero)

How to Use
Clone the repository (or download the script).

bash
Copy
Edit
git clone https://github.com/your-username/fun-calculator.git
Run the script:

Ensure Python 3.x is installed on your machine.

In your terminal, navigate to the folder where the script is saved and run:

bash
Copy
Edit
python fun_calculator.py
Input your numbers:

The program will prompt you to enter two numbers.

It will then display the sum, difference, product, and quotient of the two numbers.

Example Usage
When you run the program, it will look like this:

yaml
Copy
Edit
Enter the first number: 10
Enter the second number: 5
Results of your two numbers:
Sum: 15.0
Difference: 5.0
Product: 50.0
Quotient: 2.0
Code Breakdown
python
Copy
Edit
# Step 1: Ask the user to input the first number
num1 = float(input("Enter the first number: "))

# Step 2: Ask the user to input the second number
num2 = float(input("Enter the second number: "))

# Step 3: Do some math magic ✨
sum_result = num1 + num2
difference_result = num1 - num2
product_result = num1 * num2
quotient_result = num1 / num2

# Step 4: Show the results!
print(f"Results of your two numbers:")
print(f"Sum: {sum_result}")  # ➕
print(f"Difference: {difference_result}")  # ➖
print(f"Product: {product_result}")  # ✖️
print(f"Quotient: {quotient_result}")  # ➗
Notes
Division by Zero: The program doesn't handle division by zero yet, so be careful and don't enter zero as the second number! 😅

Decimals: This calculator works with decimals! So feel free to get fancy with your calculations. ✨

Contributing
If you’d like to add more features, fix bugs, or just make the calculator even more fun, feel free to fork the repository and submit a pull request! 🙌

License
This project is licensed under the MIT License - see the LICENSE file for details.

