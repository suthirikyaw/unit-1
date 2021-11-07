```.py

def perfectN(N):
    lst = []
    sum = 0
    for i in range(1, N):
        if N%i == 0:
            lst.append(i)
            sum += i
    if sum == N:
        perfect = "True"
    else:
        perfect = "False"

    return lst, perfect

output = perfectN(6)
print(output)

output = perfectN(10)
print(output)

C:\Users\ASUS\PycharmProjects\pythonProject2\venv\Scripts\python.exe C:/Users/ASUS/PycharmProjects/pythonProject2/main.py
([1, 2, 3], 'True')
([1, 2, 5], 'False')

Process finished with exit code 0
