# computing--project
computing sum of numbers
# Compute the sum of n numbers provided by the user

n = int(input("Enter how many numbers: "))
sum = 0

for i in range(n):
    num = float(input(f"Enter number {i + 1}: "))
    sum += num

print("Sum =", sum)
