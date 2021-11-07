```.py

def maxAbs(lst):
    biggest = 0
    for i in lst:
        if abs(i) > biggest:
            biggest = abs(i)
            biggestOutput = i
    return biggestOutput

output = maxAbs([4, 5, 2, -9, 11, 3])
print(output)

output = maxAbs([-7, 3, 1, -15])
print(output)

C:\Users\ASUS\PycharmProjects\pythonProject2\venv\Scripts\python.exe C:/Users/ASUS/PycharmProjects/pythonProject2/main.py
11
-15

Process finished with exit code 0
