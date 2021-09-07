 Given two integers A and B (A ≤ B). Print all numbers from A to B inclusively.
 
A = int(input())
B = int(input())
for i in range(A, B+1):
    print(i)
    
Given two integers A and B. Print all numbers from A to B inclusively, in ascending order, if A < B, or in descending order, if A ≥ B.

A = int(input())
B = int(input())

if A < B:
    for i in range (A, B+1):
        print(i)
else:
    for i in range (A, B-1, -1):
        print(i) 

