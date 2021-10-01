``.py

def blue_box(num1,num2):
    sum = num1 + num2
    if sum%2==0:
        return sum
    else:
        sum = 0
        return sum

output = blue_box(10,1)
print(output)


def black_box(num):
    if num > 26:
        return("?")
    else:
        code = num + 96
        return(chr(code))

output = black_box(3)
print(output)

def red_box(char1, char2):
    code1 = ord(char1)
    code2 = ord(char2)
    if code1>code2:
        return chr(code1)
    else:
        return chr(code2)

output = red_box("B","C")
print(output)
