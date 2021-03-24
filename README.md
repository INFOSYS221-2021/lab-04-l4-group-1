# Lab-04 Group 1

## Names
* Jack McGrath
* Amous Lou
* Olivia Joe-West

## Activity
1. string, integer, boolean
2. board, dupeBoard, possibleMoves
3. The board
4. ``` not (letter == 'X' or letter == 'O') ```
5. 
```
while move not in '1 2 3 4 5 6 7 8 9'.split() or not isSpaceFree(board, int(move)):
    print('What is your next move? (1-9)')
    move = input()
```
6. The list ```board``` contains the positions of each of the players as well as white space to show open positions
7. The function ```makeMove``` takes the parameters board, letter, and move. This function aims to put the letter of the player in the position they picked on the board
8. The function ```isWinner```. It puts together all the possible winning combinations together and tests if there are three in a row
9. This will not change the behaviour of the game as both statements will provide the same result. This is because the statemenet ```gameIsPlaying = False``` and break both end the while loop.
10. It keeps the loop going infinitely. The way the game stops this infinite loops is by adding
    ```
    if not playAgain():
        break
    ```
