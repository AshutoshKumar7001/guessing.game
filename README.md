# guessing.game
import random

rand_num = random.randint(1, 10000)
count =0
while count!=1:
    num = int(input(""))
    if(rand_int == num):
        print("Congratulations!! You Won !!")
        count=1
     else:
        print("Oops worng !! Try again!!")
