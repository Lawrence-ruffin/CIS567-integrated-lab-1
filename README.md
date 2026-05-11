# CIS567-integrated-lab-1
Write a program whose input is two integers. Output the first integer and subsequent increments of 5 as long as the value is less than or equal to the second integer.
first = int(input())
second = int(input())

if second < first:
    print("Second integer can't be less than the first.")
else:
    value = first
    while value <= second:
        print(value, end=" ")
        value += 5
    print()
