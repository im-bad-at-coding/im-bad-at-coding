- 👋 Hi, I’m @im-bad-at-coding
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
im-bad-at-coding/im-bad-at-coding is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
help me plz
import random

colour = [ "red" , "yellow" , "black" ]
red = [1,2,3,4,5,6,7,8,9,10]
yellow = [1,2,3,4,5,6,7,8,9,10]
black = [1,2,3,4,5,6,7,8,9,10]



def draw():
    colour_choose = random.choice(colour)
    if colour_choose == "red":
        card_num = random.choice(red)
        print("Player1 drew red " , card_num)
        red.remove(card_num)
        card_count = len(red)
        if card_count == 0:
            del(red)
            remove.colour("red")
    elif colour_choose == "yellow":
        card_num = random.choice(yellow)
        print("Player1 drew yellow " , card_num)
        yellow.remove(card_num)
        card_count1 = len(yellow)
        if card_count1 == 0:
            del(yellow)
            remove.colour("yellow")
    elif colour_choose == "black":
        card_num = random.choice(black)
        print("Player1 drew black " , card_num)
        black.remove(card_num)
        card_count2 = len(black)
        if card_count2 == 0:
            del(black)
            remove.colour("black")

    colour_choose2 = random.choice(colour)
    if colour_choose2 == "red":
        card_num3 = random.choice(red)
        print("Player2 drew red " , card_num3)
        red.remove(card_num3)
        card_count3 = len(red)
        if card_count3 == 0:
            del(red)
            remove.colour("red")
    elif colour_choose2 == "yellow":
        card_num4= random.choice(yellow)
        print("Player2 drew yellow " , card_num4)
        yellow.remove(card_num4)
        card_count4 = len(red)
        if card_count4 == 0:
            del(yellow)
            remove.colour("yellow")
    elif colour_choose2 == "black":
        card_num5 = random.choice(black)
        print("Player2 drew black " , card_num5)
        black.remove(card_num5)
        card_count5 = len(red)
        if card_count5 == 0:
            del(black)
            remove.colour("black")

draw()

###########
Traceback (most recent call last):
  File "\\AHS-DATA01\Pupils\17\17longstaffb\Documents\Desktop\card alternate.py", line 63, in <module>
    draw()
  File "\\AHS-DATA01\Pupils\17\17longstaffb\Documents\Desktop\card alternate.py", line 13, in draw
    card_num = random.choice(red)
UnboundLocalError: local variable 'red' referenced before assignment




what is this





