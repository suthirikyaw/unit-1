```.py

def largestDistance(A, B, C):
    if A > B and A > C:
        biggest = A
    elif B > A and B > C:
        biggest = B
    else:
        biggest = C

    if A < B and A < C:
        smallest = A
    elif B < A and B < C:
        smallest = B
    else:
        smallest = C

    largest = biggest - smallest
    return largest

output = largestDistance(1, 2, 3)
print(output)

output = largestDistance(1, 3, 10)
print(output)

output = largestDistance(3, 2, 4)
print(output)

C:\Users\ASUS\PycharmProjects\pythonProject2\venv\Scripts\python.exe C:/Users/ASUS/PycharmProjects/pythonProject2/main.py
2
9
2

Process finished with exit code 0
