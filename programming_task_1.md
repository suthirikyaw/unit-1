# Programming task 1
### Ask the user for  2 numbers, A and B, Output TRUE if one of them is 10 or if their sum is 10.

```.py

A = int(input("Please enter a number: "))
B = int(input("Please enter a number: "))

if A == 10 or B == 10:
  print("TRUE")
elif A + B == 10:
  print("TRUE")
else:
  print("FALSE")
  
  
