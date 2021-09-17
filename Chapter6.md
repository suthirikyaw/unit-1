# WHILE LOOPS

# Lists of Squares
### For a given integer N, print all the squares of integer numbers where the square is less than or equal to N, in ascending order

n = int(input())

i = 1

while i**2 <= n:

    print(i**2)
    
    i += 1
    
# Least divisor    
### Given an integer not less than 2. Print its smallest integer divisor greater than 1.

n = int(input())

i = 2

while n % i != 0:

    i += 1
    
print(i)

# The Power of Two
### For a given integer N, find the greatest integer x where 2x is less than or equal to N. Print the exponent value and the result of the expression 2x.
### Don't use the operation **.

n = int(input())

power = 2

x = 1

while power <= n:

    power = power* 2
    
    x += 1
    
print(x - 1, power // 2)

# Morning jog
### As a future athlete you just started your practice for an upcoming event. Given that on the first day you run x miles, and by the event you must be able to run y miles.
### Calculate the number of days required for you to finally reach the required distance for the event, if you increases your distance each day by 10% from the previous day.
### Print one integer representing the number of days to reach the required distance.

x = int(input())

y = int(input())

counter = 1

while x < y:

    counter += 1
    
    x = x*1.10
    
print(counter)

# The length of the sequence
### Given a sequence of non-negative integers, where each number is written in a separate line. Determine the length of the sequence, where the sequence ends when the integer is ### equal to 0. Print the length of the sequence (not counting the integer 0). The numbers following the number 0 should be omitted.

num = int(input())

counter = 0

while num != 0:

    counter += 1
    
    num = int(input())
    
print(counter)

# The sum of the sequence
### Determine the sum of all elements in the sequence, ending with the number 0.

num = int(input())
sum = 0

while  num != 0:
    sum += num
    num = int(input())

print(sum)

# The average of the sequence
### Determine the average of all elements of the sequence ending with the number 0.

num = int(input())
sum = 0
counter = 0

while num != 0:
    sum += num
    counter += 1
    num = int(input())

print(sum/counter)
    
