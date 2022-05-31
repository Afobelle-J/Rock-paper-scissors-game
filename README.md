# Rock-paper-scissors-game
import random
List=['Rock', 'Paper', 'Scissors']
Player=str(input('Rock, Paper, Scissors :'))
CPU=random.choice(List)
if Player == CPU:
    print("Both players selected {Player}. It's a tie!")
elif Player == "rock":
    if CPU == "scissors":
        print ("Rock smashes scissors! You win!")
    else:
        print ("Paper covers rock! You lose.")
elif Player == "paper":
    if CPU == "rock":
        print ("Paper covers rock! You win!")
    else: 
        print ("Scissors cuts paper! You lose.")
elif Player == "scissors":
    if CPU == "paper":
        print ("Scissors cuts paper! You win!")
    else:
        print("Rock smashes scissors! You lose.")

