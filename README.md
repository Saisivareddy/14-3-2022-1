# 14-3-2022-1
x = int(input("User Input: "))

count_of_digits = 0

while x > 0:

   x = int(x/10)

   count_of_digits += 1

print("Number of Digits: ",count_of_digits)
