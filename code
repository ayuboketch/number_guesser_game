#Guessing Game
import random
#guess = random(0, 11)
count = 3
#limit_count = 3
print("welcome to my random number guessing game".title())
name = input("What is your name: ").title()
number = int(random.randint(0, 10))
print(number)
if input(f"Do you want to play {name}?: ").lower() != "yes":
    quit("You quit the game")
else:
    print(f"{name}, guess a number between 0 and 10, Lets GO!")
    if int(input("Guess a number: ")) == number:
        print("Huh, you guessed it!, on your first try no less")
        quit("You won!")
    elif input != number:
        count -= 1
        print(f"sorry, that is not the correct number, you have {count} attempts left")

    if int(input("Guess a number: ")) == number:
        print("Huh, you guessed it!, on your second try no less")
        quit("You won!")
    elif input != number:
        count -= 1
        print(f"sorry, that is not the correct number, you have {count} attempts left")

    if int(input("Guess a number: ")) == number:
        print("Huh, you guessed it!, on your last try no less")
        quit("You won!")
    elif input != number:
        count -= 1
    else:
        print(f"sorry, that is not the correct number, you have {count} attempts left")
    print(f"You have {count} points {name}, you can start again if you want to.")
