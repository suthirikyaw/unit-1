### When capitalize = True, output the phrase with capitals but when capitalize = False, output the phrase but in lowercase

```.py
def mystery_box1(phrase, tof):
    lst = []
    phraselen = len(phrase)
    count = 1
    if tof == False:
        phrase = phrase.lower()
        for i in range(0, phraselen):
            lst.append(phrase[phraselen - count])
            count += 1
        lst = ''.join(lst)
        return lst
    else:
        for i in range(0, phraselen):
            lst.append(phrase[phraselen - count])
            count += 1
        lst = ''.join(lst)
        return lst

output = mystery_box1("Hello", False)
print(output)

output = mystery_box1("Hello", True)
print(output)

### Output the name and the last part of a gmail address

def mystery_box2(gmail):
    dotcount = 0
    for char in gmail:
        if char != ".":
            dotcount += 1
        else:
            break
    firstname = gmail[0:dotcount]
    address = 0
    for char in gmail:
        if char != "@":
            address += 1
        else:
            break
    lastname = gmail[dotcount + 1:address]

    count = 0
    for char in gmail:
        if char != " ":
            count += 1
        else:
            break
    end = gmail[address+1:count]
    return (firstname + " " + lastname + "," + end)

output = mystery_box2("john.doe@gmail.com")
print(output)

output = mystery_box2("su.thiri@gmail.com")
print(output)
