# Programming Task 2
### Strange Numbers: Given a number as a String N. Multiply all of its digits, and repeat the same with the product obtained till the product consists of only one digit. Output the number of steps taken to do so. 

```.py

N = input("Please enter a number: ")
counter = 0
while int(N) > 9:
  tens = int(int(N)/10)
  ones = int(N) - (tens*10)
  N = tens*ones
  counter +=1

print(counter)
