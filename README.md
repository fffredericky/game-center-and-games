


# Notes on implementation:
1. WE HAVE A MAX OF ONE SAVED GAME PER DIFFICULTY, PER GAME:  
For Example: You can have a saved game for SlidingTiles Easy, SlidingTiles Medium and MineSweeper Medium
at the same time. This makes sense because most mobile games have this design choice.  
2. WE HAVE NO SAVED BUTTON BECAUSE WE AUTOSAVE EVERY TURN
3. ONCE YOU WIN/COMPLETE A GAME, THE SAVE IS ERASED AND YOU HAVE TO START A NEW GAME
4. WE CHOSE TO FIX THE DIFFICULTIES TO EASY, MEDIUM AND HARD   
5. WE SELECT DIFFICULTY FIRST BECAUSE YOU CAN HAVE DIFFERENT SAVED GAMES DEPENDING ON DIFFICULTY  
6. WHEN YOU LOSE A GAME, YOUR SAVE IS ERASED SO YOU CAN START A NEW GAME
7. WHEN YOU LOAD AN OLD SAVED GAME, YOU HAVE NO UNDO'S (UNDOS ARE RESET AFTER EXITING THE GAME)
