##### we welcome contributions for improvement!
###### this is meant to help you with your decisions and it's basically for fun.
> Please follow the life decisions simulation. 

print("You heard knocking from the front door and you open the door.")
print("you see someone there.")
Q1 = input("Who did you see? The Ugly old goblin or The beautiful Fae: ")
print("\n")
if "goblin" in Q1:
    print("The Ugly old goblin with otherworldly knowledge is there.")
    Q2_goblin = input("Will you welcome him? _yes or no_: ")
    if Q2_goblin == "yes": 
        print("He is grateful for your hospitality and shares his knowledge with you.")
        print("\n")
    elif Q2_goblin == "no":
        print("He curses you, and now, you lose everything! The end.")
    Q3_goblin = input("You came home, reflecting on the bad decision you had made. _Do you ask the ugly Goblin for advice, or do you keep it to yourself_?: ")
    if Q3_goblin == "yes" or "advice":
        print("You ask for an advice! you get the benefit of having a wise roommate! The end.")
    elif Q3_goblin == "no" or "keep":
        print("You kept to yourself like a sulking loser and that mistake will haunt you for the rest of your life! the end.")
    else:
        print("Since you can't decide, you just wasted the goblin's time and he pities you! The end")
        print("\n")
elif "fae" in Q1:
    print("The beautiful Fae, who is skilled with magic, is there.")
    Q2_fae = input("Will you welcome them? _yes or no_?: ")
    if Q2_fae == "yes":
        Q3_fae = input("They ask for your name. _Will you give your name_?: ")
        if Q2_fae == "yes" and Q3_fae == "no":
            print("you invite them but didn't say your name.")
            print("The fae respects you and left")
            print("\n")
        elif Q3_fae == "yes":
            print("You gave them your name. You are now under the fae's control forever! The end.")
else:
    print("Please pick someone and don't just stare at the door, weirdo!")