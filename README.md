# Take three numbers as input
num1 = loat(input("Enter firs number: "))
num2 = float(input("Enter second number: "))
num3 = float(input("Enter third number"))

# Compare using conditional statements
if (num1 >= num2) and (num1 > num3):
    largest = num1
elif (num2 > num1) and (num2 >= num3):
    largest = num2
else
    largest = num

print(The largest number is:",largest)

# Alternative one-lineapproach using built-in max()
# largest = max(num1, num2, num3)

