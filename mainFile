# This is a header for the application
# You should read this header and insert your name and your date below as part of the peer review
# This is a typical part of any program
# Author: Gavin Bernard
# Creation Date: 2/12/2022
# Below is a simple program with 10 issues (some are syntax errors and some are logic errors.  You need to identify the issues and correct them.

import random
import time

def displayIntro():
        print('''You are in a land full of dragons. In front of you,
you see two caves. In one cave, the dragon is friendly
and will share his treasure with you. The other dragon
is greedy and hungry, and will eat you on sight.''')
        print()

def chooseCave():
        cave = ''
        while cave != '1' and cave != '2':
                print('Which cave will you go into? (1 or 2)')
                cave = input()

        return cave

def checkCave(chosenCave):
        print('You approach the cave...')
        #sleep for 2 seconds
        time.sleep(2)
        print('It is dark and spooky...')
        #sleep for 2 seconds
        time.sleep(2)
        print('A large dragon jumps out in front of you! He opens his jaws and...')
        print()
        #sleep for 2 seconds
        time.sleep(2)
        friendlyCave = random.randint(1, 2)

        if chosenCave == str(friendlyCave):
                print('Gives you his treasure!')
        else:
                print('Gobbles you down in one bite!')

playAgain = 'yes'
while playAgain == 'yes' or playAgain == 'y':
        displayIntro()
        caveNumber = chooseCave()
        checkCave(caveNumber)

        playAgain = ''
        choices = {'yes', 'y', 'no', 'n'}

        while playAgain not in choices:
                print('Do you want to play again? (yes or no)')
                playAgain = input()
                if playAgain == "no" or playAgain == 'n':
                        print("Thanks for playing!")


'''
        [List of Errors (Personal Use)]
1. 'Playing' is spelled incorrectly in the end message.
2. time.sleep(3) should be time.sleep(2)
3. chooseCave uses incorrect spacing.
4. while playAgain = 'yes' should be comparative and use '==', not '='.
5. caveNumber = choosecave() should call chooseCave() instead.
6. chooseCave should return cave, not caves.
7. The bottom chosenCave message does not use parenthesis.
8. The "Thanks for playing!" message does not include 'n', just 'no.'
9. The formatting for displayIntro is off, requiring changing each line to a print statement or removing the indents.
10. The playAgain string does not check for if the user selects something other than yes or no.
'''
