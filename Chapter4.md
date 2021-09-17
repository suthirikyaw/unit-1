# Given two integers A and B (A ≤ B). Print all numbers from A to B inclusively.
 
A = int(input())

B = int(input())

if A<=B:

 for i in range(A, B+1):

    print(i)
    
else:

    print("Wrong values")
    
# Given two integers A and B. Print all numbers from A to B inclusively, in ascending order, if A < B, or in descending order, if A ≥ B.

A = int(input())

B = int(input())

if A < B:

    for i in range (A, B+1):
    
        print(i)
        
else:

    for i in range (A, B-1, -1):
    
        print(i) 

# 10 numbers are given in the input. Read them and print their sum. Use as few variables as you can.

sum = 0

for i in range(10):

    num = int(input())
    
    sum += num

print(sum)

# N numbers are given in the input. Read them and print their sum.
# The first line of input contains the integer N, which is the number of integers to follow. Each of the next N lines contains one integer. Print the sum of these N integers.

sum = 0

N = int(input())

for i in range(N):

    num = int(input())
    
    sum += num
    
print(sum)

# For the given integer N calculate the following sum:
# 1^3+2^3+…+N^3

N = int(input())

sum = 0

for i in range(1, N+1):

    sum += (i*i*i)

print(sum)

# In mathematics, the factorial of an integer n, denoted by n! is the following product:
# n!=1×2×…×n
#  For the given integer n calculate the value n!. Don't use math module in this exercise.

product = 1

n = int(input())

for i in range(1, n+1):
    
    product = product * i

print(product)

# Given N numbers: the first number in the input is N, after that N integers are given. Count the number of zeros among the given integers and print it.
# You need to count the number of numbers that are equal to zero, not the number of zero digits.

N = int(input())

counter = 0

for i in range(N):
    
    num = int(input())
    
    if num == 0:
        
        counter += 1

print("Number of zeroes: ", counter)

# Given an integer n, print the sum 1!+2!+3!+...+n!.
# This problem has a solution with only one loop, so try to discover it. And don't use the math library :)

product = 1

sum = 0

n = int(input())

for i in range(1, n+1):

  product *= i
  
  sum += product 

print(sum)

# For given integer n ≤ 9 print a ladder of n steps. The k-th step consists of the integers from 1 to k without spaces between them.
# To do that, you can use the sep and end arguments for the function print().

n = int(input())

for i in range(1, n+1):
    
    for j in range(1, i+1):
        
        print(j, sep = "", end = "")
        
    print()
