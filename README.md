# README
#Guess The Number
import random

times = int(input('How many times do you want to play?:'))
for i in range(times):
    user_number = int(input('Guess the number from 0 to 9:'))
    number = random.randint(0,9)
    if user_number == number:
        print('Well done you found the number!!!')
    else:
        print("Doesn't matter you will gonna find it next time!")
