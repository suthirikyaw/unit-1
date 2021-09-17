# For a given integer N, print all the squares of integer numbers where the square is less than or equal to N, in ascending order.

n = int(input())
i = 1

while i**2 <= n:
    print(i**2)
    i += 1
    
# Given an integer not less than 2. Print its smallest integer divisor greater than 1.

n = int(input())
i = 2
while n % i != 0:
    i += 1
print(i)

# For a given integer N, find the greatest integer x where 2x is less than or equal to N. Print the exponent value and the result of the expression 2x.
# Don't use the operation **.

n = int(input())
power = 2
x = 1
while power <= n:
    power = power* 2
    x += 1
print(x - 1, power // 2)

