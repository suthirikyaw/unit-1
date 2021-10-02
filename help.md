```.py

def Instructions():
    valid = False
    print("Welcome. Do you wish to skip this tutorial?")

    while valid == False:
        skip = input("(Y/N) >> ")
        if skip == "N" or "n":
            print("Whenever you see this symbol (>) at the end of the sentence, please press enter to continue. >")
            enter = input()
            print("This game is based on the choices and decisions. Unless otherwise specified, you will be asked to choose between given options. >")
            enter = input()
            print("You will be mainly using numbers to make your decisions. When you see this symbol (>>) you will enter your choice. >")
            enter = input()
            print("For example: How do you feel about pineapple on pizza? \n"
                "1. I hate it \n"
                "2. I love it \n"
                "3. I've never tried it before")
            pizza = int(input(">> "))
            if pizza == 1:
                print("Good. When machines finally take over Earth, you will be spared. >")
            elif pizza == 2:
                print("What is wrong with you. You will be the first to go when machines take over. >")
            else:
                print("Good. Keep it that way. >")
            enter = input()
            print("Anyways, enough about pizzas. Now that you know how to play, without further ado, on with the game...")
            print("Loading......")
            valid = True
        elif skip == "Y" or "y":
            print("Okay, Know-It-All. Since you already know how the game works, without further ago, on with the game....")
            valid = True
        else:
            print("Please enter only Y or N: ")
            valid = False
