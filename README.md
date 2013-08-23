#this is a text based game
#use your imagination!
import time
import random
def choosePerson():
    joe = 'joe'
    person = ' '
    while person != 'joe' and person != 'bob':
        print ('who will it be?')
        person = input()
        
    if person == 'joe':
        meetJoe2()
    else:
        meetBob2()

def meetBob():
    print ("BOB : Hello your name is...")
    name = input()
    time.sleep (2)
    print(name + "!!!")
    time.sleep (1)
    print ('BOB : Hmmm..', end= '')
    time.sleep (1)
    print ('.', end= '')
    time.sleep (1)
    print ('.')
    time.sleep (1)
    print ('BOB : Oh, never mind! Welcome to  Anilorac!')

def meetJoe():
    print ("JOE : What do you want?!?")
    time.sleep (1)
    print ("JOE : Oh, so you are the new kid...")
    time.sleep (1)
    print ("JOE : GO AWAY!!! i'm very busy!!!!!!")
    time.sleep (1)

def meetBob2():
    print ("BOB : Hello your name is...")
    time.sleep (2)
    print(name + "!!!")
    time.sleep (1)
    print ('BOB : Hmmm..', end= '')
    time.sleep (1)
    print ('.', end= '')
    time.sleep (1)
    print ('.')
    time.sleep (1)
    print ('BOB : Oh, never mind! Welcome to  Anilorac!')
    time.sleep (3)
    print ("ARTHUR : let's go meet Joe!")
    time.sleep (2)
    meetJoe()

def meetJoe2():
    print ("JOE : What do you want?!?")
    time.sleep (2)
    print ("JOE : Oh, so you are the new kid...")
    time.sleep (2)
    print ("JOE : GO AWAY!!! i'm very busy!!!!!!")
    time.sleep (2)
    print ("ARTHUR : Let's go meet Bob!")
    time.sleep (2)
    meetBob()


print ("hello, i'm not sure we have met.")
print ("what is your name?")
name = input()
print ("It is good to meet you" + name)
print ("welcome to the world of anilorac!")
time.sleep (2)
print("My name is Arthur, and I will be your guide!")
time.sleep (2)
print ("ARTHUR : Who would you like to meet first?")
time.sleep (2)
print ("ARTHUR : Joe or Bob?")
choosePerson()



