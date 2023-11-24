TIC - TAC - TOE 

Figma link: https://www.figma.com/file/scaXCU6pGmXTSwaBk9xNXj/Tick-tac-toe-Task?type=design&node-id=0-1&mode=design

Features

-> Build the UI similar to the figma design

-> User should be able to provide their input

-> For computer you can randomly make a selection for their turn

-> You need to show 3 type of scores based on gameplay: win by user, win by computer and tie

-> You need to store the scores in localstorage

-> You need to add the quote API https://api.adviceslip.com/ and every 1 min you need to refresh the quote with a new one

-> You need implement share feature, to share the game with your friends

-> Add a toast message on "Invite your friend"

Checklist-1

-> Build the home page of the tic tac toe

-> Home page will have gameplay area, quote section, choose player, new game options with share feature

-> Add the quote section

-> Invite a friend with toast message

-> For toast you can use any package as per your preference

Checklist-2

-> You need build the gaming page where the user start to play the game

-> Human and PC can play their turn respectively

-> Show the current player turn

-> You need to save the choice of the player in local storage from the first screen between O and X

-> For every game play the first player to start the game will be USER/HUMAN irrespective of symbols between X and O

-> You need to implement the logic for PC, so you need to pick a random spot which is empty and allow computer to play his turn. No need to check for whether HUMAN is winning or not, not need to check for blocking the HUMAN turn if he/she is winning

Checklist-3

-> You need to implemented the logic to calculate the score

-> You need to show the score section and save the scores in localstorage for every gameplay session

-> You need to implement the logic to block the PC/Human to win against the computer

-> If the user refreshes the page in the middle the of the game then, user should not be taken to home page

Checklist-4

-> Add popup to reset the game when user click on refresh icon, in this case there will be two options, first option is Play Again which is equivalent to a New Game where scores and blocks will be reset, but the symbol will remain the same.

-> Add popup which will appear after every game, in the popup you will have two options Next Round and Quit. Next round will move you to the next game without resetting the scores.

Quit - Take to home screen and reset the score & symbol choice

Play again - Reset the score & grid boxes but not the symbol choice

Next round - Clears the grid boxes and retain the score for next round
