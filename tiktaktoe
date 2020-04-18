import time
p1 = str(input('Player 1 choose x or o:  '))
if p1 == 'x':
    p2 = str('o')
    print('player 2 is o')
else:
    p2 = str('x')
    print('player 2 is x')
def game():
    board = [0,1,2,3,4,5,6,7,8,]
    
    def show():
        print(board[0],'|',board[1],'|',board[2],'|')
        print('___________')
        print(board[3],'|',board[4],'|',board[5],'|')
        print('___________')
        print(board[6],'|',board[7],'|',board[8],'|')
        print('___________')
    show()
    for i in range(9):
        spot = int(input('Enter a spot:'))
        if board[spot] != 'x' and board[spot] != 'o':
            board[spot]= input('Enter your char:')
            if board[spot] == p1:
                print('Player 2 your turn')
            else:
                print('player 1 your turn')
        else:
            print('spot is taken')
        time.sleep(0.5)    
        show()
        
        if board[0]==board[1]==board[2]=='x' or board[3]==board[4]==board[5]=='x' or board[6]==board[7]==board[8]=='x' or board[0]==board[3]==board[6]=='x' or board[1]==board[4]==board[7]=='x' or board[2]==board[5]==board[8]=='x' or  board[0]==board[4]==board[8]=='x' or board[2]==board[4]==board[6]=='x':
           time.sleep(0.5)    
           print('player 1 won')
           break;
        elif board[0]==board[1]==board[2]=='o' or board[3]==board[4]==board[5]=='o' or board[6]==board[7]==board[8]=='o' or board[0]==board[3]==board[6]=='o' or board[1]==board[4]==board[7]=='o' or board[2]==board[5]==board[8]=='o' or board[0]==board[4]==board[8]=='o' or board[2]==board[4]==board[6]=='o':
           time.sleep(0.5)    
           print('Player 2 won')
           break;
        
    else:
        print('Game over')

    def scoreboard():
       p1score = 0
       p2score = 0
       if board[0]==board[1]==board[2]=='x' or board[3]==board[4]==board[5]=='x' or board[6]==board[7]==board[8]=='x' or board[0]==board[3]==board[6]=='x' or board[1]==board[4]==board[7]=='x' or board[2]==board[5]==board[8]=='x' or  board[0]==board[4]==board[8]=='x' or board[2]==board[4]==board[6]=='x':
           p1score = p1score + 1
       elif board[0]==board[1]==board[2]=='o' or board[3]==board[4]==board[5]=='o' or board[6]==board[7]==board[8]=='o' or board[0]==board[3]==board[6]=='o' or board[1]==board[4]==board[7]=='o' or board[2]==board[5]==board[8]=='o' or board[0]==board[4]==board[8]=='o' or board[2]==board[4]==board[6]=='o':  
           p2score = p2score +1
       else:
           time.sleep(0.5)    
           print('It is a tie')
       time.sleep(0.5)    
       print('PLayer 1:',p1score)
       print('Player 2:',p2score)
    scoreboard()
game()


   
