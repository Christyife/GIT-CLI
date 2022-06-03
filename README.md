# GIT-CLI
# Rock Paper Scissors game

print("welcome to the Rock, Paper, Scisssors game")

is_running = True

while is_running:
    #processing game...
    print("Starting Game")
    print("enter R for Rock, P for Paper, S for scissors")
    user_operation = input("what Letter would you like to pick?nPick any of ['R', 'P', 'S',] : ")
    a = input('pick R, P, S')
    for letter in a:
        if letter in a:
            continue
        else:
            break
            print('value entered not valid')
    import random   
    computer_choice = random.choice(a)
    print('your choice is: ', a)
    print('computer_choice is: ', computer_choice)

    if a == computer_choice:
        print('it is a tie')

    elif a == 'R' and computer_choice == 'p':
        print('computer wins')

    elif a =='P' and computer_choice =='R':
            print('congratulations you win')

    elif a == 'S' and computer_choice =='R':
        print('computer wins')

    elif a == 'S' and computer_choice == 'P':
        print('congratulations you win')

    elif a not in a:
        print('wrong input')
    print('Do you want to play again? y or n')
    d = input('enter y to continue or n to end: ')
    if d =='y':
        continue
    
    if d =='n':
        is_running = False
        # This the same thing as break                  

print('Thanks for playing the game, bye bye...') 

# ctrl + c to exit any python program
