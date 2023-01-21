# snake-water-game
print("SNAKE WATER GUN\n  Enter 0 for GUN GAME\n  Enter 1 for SNAKE\n  Enter 2 for WATER\n\n")
user=int(input("ENTER YOUR OPTION USER\n"))
computer=int(input("ENTER YOUR OPTION COMPUTER\n"))
if(user==0 and computer==0 or user==1 and computer==1 or user==2 and computer==2):
    print("draw")
elif(user==0 and computer==1):
    print("USER WINNS YAYY!!")
elif(user==0 and computer==2):
    print("COMPUTER WINNS YAYY!!")
elif(user==1 and computer==0):
    print("COMPUTER WINNS YAYY!!")
elif(user==1 and computer==2):
    print("USER WINNS YAYY!!")
elif(user==2 and computer==0):
    print("USER WINNS YAYY!!")
else:
    print("COMPUTER WINNS YAYY!!")
