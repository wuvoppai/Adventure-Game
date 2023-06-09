# Adventure-Game


n=input("Type your name: ")
print("Welcone", n, "to this adventure\n")
a=input("You are on a dirt road, it has come to an end and you can go left or right which way would you like to go (left/right)? \n").lower()
if a== "left":
    a=input("You come to a river, you can walk around it or swim around (swim or walk around)? \n").lower()
    if a == "swim":
        print("You swam across and were eaten by an alligator.\n")
    elif a=="walk around":
        print("You walked for miles, ran out of water and died.\n")
elif a =="right":
    a=input("You come to a bridge, it looks wobbly, do you want to cross it or head back(cross/back) \n").lower()
    if a== "back":
        print("You go back and lose.")
    elif a== "cross":
        a=input("You cross the bridge and meet a stranger. Do you want to talk to them (yes/no)? \n").lower()
        if a== "yes":
            print("You talked to the strsanger and they give you gold. \nYOU WIN!!!")
        elif a=="no":
            print("You ignore the stranger and they are offended. \nYOU LOSE!!")
        else:
            print("Not a valid option. you lose.")

    

else:
    print("Not a valid option. you lose.")
