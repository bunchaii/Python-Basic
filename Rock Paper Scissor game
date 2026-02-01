import random, sys

# variables
wins = 0
losses = 0
ties = 0

# main loop
while True:
    print ('%s Wins, %s Losses, %s Ties'%(wins, losses, ties))
    while True:
        print('enter your choices: r, p, s or q')
        player_input = input('')
        if player_input == 'q':
            sys.exit()
        if player_input == 'r' or player_input == 'p' or player_input == 's':
            break
    #print('type your choice: r, p, s')
    # display of player choices
    if player_input == 'r':
        print('rock vs ...')
    elif player_input == 'p':
        print('paper vs ...')
    elif player_input == 's':
        print('scissors vs ...')
    # display computer choices
    move_num = random.randint(1,3)
    if move_num == 1:
        computer_move = 'r'
        print('rock')
    elif move_num == 2:
        computer_move = 'p'
        print('paper')
    elif move_num == 3:
        computer_move = 's'
        print('scissors')
    # record win or loss or ties
    if player_input == computer_move:
        print('ties')
        ties = ties + 1
    elif player_input == 'r' and computer_move == 'p':
        print('loss')
        losses = losses + 1
    elif player_input == 'r' and computer_move == 's':
        print('win')
        wins = wins + 1
    elif player_input == 's' and computer_move == 'p':
        print('win')
        wins = wins + 1
    elif player_input == 's' and computer_move == 'r':
        print('loss')
        losses = losses + 1
    elif player_input == 'p' and computer_move == 's':
        print('loss')
        losses = losses + 1
    elif player_input == 'p' and computer_move == 'r':
        print('win')
        wins = wins + 1
