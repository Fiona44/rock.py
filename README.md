
#FIONA GATHONI MWENDA
#Exercise 2.1
#Homework_1.py
#4th May 2018

#rules:rock beats scissors,paper beats rock,scissors beat paper
import random
#player1 choice function
def rock(): hard 
def paper(): soft 
def scissors():sharp
def player2(): second_player
def player2_choice(): rock,paper,scissors
def rps(): 
    player1_choice=(rock,paper,scissors)
    if player1_choice==rock:
         player1_choice_rock()
    elif player1_choice==scissors:
        player1_choice==scissors()
    else: player1_choice_paper()
#when player1 chooses rock
def player2(): second_player
def player1_choice_rock():
        player2_choice=raw_input(rock,paper,scissors)
        if player2_choice==rock:
            print 'a tie. Both Players choose rock.'
        try_again()
        if player2_choice==paper:
            print 'player2 wins. Paper beats rock.'
        if player2_choice==scissors:
            print 'player1 wins. Rock beats scissors.'

        else: print'try again'
        player1_choice_rock()
#when player1 chooses paper
def player2(): second_player
def player1_choice_paper():
            if player2_choice==rock:
                print 'player1 wins. paper beats rock.'
            try_again()
            if player2_choice==papaer:
                print 'a tie. Both choose paper.'
            try_again()
            if player2_choice==scissors:
                print 'player2 wins. Scissors beats paper.'
            try_again()

            
#when player1 chooses scissors
def player2(): second_player
def player1_choice_scissors():
                if player2_choice==rock:
                    print 'player2 wins. Rock beats scissors.'
                try_again()
                if player2_choice==paper:
                    print 'player1 wins. Scissors beats paper.'
                try_again()
                if player2_choice==scissors:
                    print 'a tie. Both choose scissors.'
                try_again()
                
#try again function
def try_again():
                choice=raw_input('play again? yes or no')
                if choice=='yes':
                    rps()
                elif choice=='no':
                    quit()
                else: print 'try again'
                try_again()
rps()
