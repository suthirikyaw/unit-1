```.py
def MixStart(string):
    ix = string[1:3]
    if ix == "ix":
        return_ = 'True'
    else:
        return_ = 'False'
    return return_

output = MixStart('mix Snacks')
print(output)

output = MixStart('pix Snacks')
print(output)

output = MixStart('piz Snacks')
print(output)

C:\Users\ASUS\PycharmProjects\pythonProject2\venv\Scripts\python.exe C:/Users/ASUS/PycharmProjects/pythonProject2/main.py
True
True
False

Process finished with exit code 0
