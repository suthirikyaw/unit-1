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
