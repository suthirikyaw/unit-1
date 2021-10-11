
```.py
def mysterybox_Pablo(phrase):
    counter = 0
    for i in phrase:
        if i == "o" or i == "O":
            counter += 1
    return counter

output = mysterybox_Pablo("onomatopoeia")
print(output)

C:\Users\ASUS\PycharmProjects\pythonProject2\venv\Scripts\python.exe C:/Users/ASUS/PycharmProjects/pythonProject2/main.py
4

Process finished with exit code 0

