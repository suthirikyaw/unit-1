```.py

def letters(string):
    returnMessage = []
    stringLen = len(string)
    counter = 0
    while counter < stringLen:
        for letter in string:
            message = (f"{counter} = {letter}")
            print(message)
            counter += 1

output = letters('hello')
print(output)

output = letters('python')
print(output)

C:\Users\ASUS\PycharmProjects\pythonProject2\venv\Scripts\python.exe C:/Users/ASUS/PycharmProjects/pythonProject2/main.py
0 = h
1 = e
2 = l
3 = l
4 = o
None
0 = p
1 = y
2 = t
3 = h
4 = o
5 = n
None

Process finished with exit code 0
