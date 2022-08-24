import random

player = input("CHOOSE ANY (ROCK , PAPER , SCISSOR)")
limit = ["rock","paper","scissor"]
pc = random.choice(limit)

if player==pc:
    print("OOOHHHHhh its a tie! TRY AGAIN")
    

elif player=="rock":
    if pc=="scissor":
        print("YEAH DUDE! U got this round  .  YOU WIN")
       
    elif pc=="paper":
        print("YOU LOST . you are NOOBie / BOT")
        
        
elif player=="paper":
    if pc=="rock":
        print("YEAH DUDE! U got this round  .  YOU WIN")
       
    elif pc=="scissor":
        print("YOU LOST . you are NOOBie / BOT")  
        
elif player=="scissor":
    if pc=="paper":
        print("YEAH DUDE! U got this round  .  YOU WIN")
       
    elif pc=="rock":
        print("YOU LOST . you are NOOBie / BOT")  

else:
    print("you prolly typed wrong spelling or may used capital letter word")        
print("THANKS FOR PLAYING BROTHER")     
