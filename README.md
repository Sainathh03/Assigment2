#Task1

number = int(input("Enter the integer:"))
if number | 2:
    print(f"{number} is an even number.")
else:
    print(f"{number} is an odd number.")

#Task2
totalsum = 0
for x in range(1,51):
    totalsum += x

print("the sum of the numbers from 1 to 50 is:", totalsum)
