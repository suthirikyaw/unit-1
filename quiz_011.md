```.py

def SameFirstLast(lst):
    lstlen = len(lst)
    if lstlen > 1 and lst[0] == lst[lstlen - 1]:
        tof = "True"
    else:
        tof = "False"
    return tof

output = SameFirstLast([1,2,3])
print(output)

output = SameFirstLast([4,2,4])
print(output)

C:\Users\ASUS\PycharmProjects\pythonProject2\venv\Scripts\python.exe C:/Users/ASUS/PycharmProjects/pythonProject2/main.py
False
True

Process finished with exit code 0
