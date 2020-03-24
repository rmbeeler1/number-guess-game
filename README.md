# number-guess-game
# My first project


print('Welcome to the guessing game, are you ready to go? ')
print('Guess the number I am thinking of from 1 to 500')
import time
import random 
number = random.randint(1,501)
time1 = time.time()
while True:
    guess = int(input('What is your guess? '))
    if guess > number:
        print("That's too high! ")
    elif guess < number:
        print("That's too low! ")
    elif guess == str():
        print('You got to enter a number, come on man! ')
    elif guess == number:
        break
time.sleep(1)

print("You've guess the number. Congrats! ") 

time2 = time.time()

total_time = time2 - time1

print('It only took you', total_time, 'seconds')
