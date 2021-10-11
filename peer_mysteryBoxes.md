
```.py
def mysterybox_Pablo(phrase):
    counter = 0
    for i in phrase:
        if i == "o" or i == "O":
            counter += 1
    return counter

output = mysterybox_Pablo("onomatopoeia")
print(output)

output = mysterybox_Pablo("balloon")
print(output)

output = mysterybox_Pablo("barbie")
print(output)

C:\Users\ASUS\PycharmProjects\pythonProject2\venv\Scripts\python.exe C:/Users/ASUS/PycharmProjects/pythonProject2/main.py
4
2
0

Process finished with exit code 0


def mystery_Beril(phrase1, phrase2):
    counter1 = 0
    counter2 = 0
    for i in phrase1:
        for j in phrase1:
            if i == j:
                counter1 += 1
    for i in phrase2:
        for j in phrase2:
            if i == j:
                counter2 += 1
    if counter1 > counter2:
        return phrase1
    else:
        return phrase2

output = mystery_Beril("balloon", "pumpkin")
print(output)

output = mystery_Beril("pumpkin", "balloon")
print(output)

output = mystery_Beril("banana", "carry")
print(output)

C:\Users\ASUS\PycharmProjects\pythonProject2\venv\Scripts\python.exe C:/Users/ASUS/PycharmProjects/pythonProject2/main.py
balloon
balloon
banana

Process finished with exit code 0



