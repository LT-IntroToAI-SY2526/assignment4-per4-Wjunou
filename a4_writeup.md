# Assignment 4 - Writeup

In assignment 4 we created a basic tic tac toe game so that we could learn object oriented programming. Respond to the following questions.

## Reflection Questions

1. What was the most difficult part to tic-tac-toe? The most difficult part of this assigment was the has won function the difficult stems from the multitude of possiblities that a player can win in a game of tik tak toe.

2. Explain how you would add a computer player to the game. I'd create a computer opponent by writing a function that automatically picks moves instead of asking for player input. The function would scan the board to find empty spaces where neither player has gone yet. Then, it would try to be smart about which spot to choose-either going for a winning move if one's available, or blocking the opponent from winning on their next turn. This should make an AI that's actually challenging to play against.

3. If you add a computer player, explain (doesn't have to be super technical) how you might get the computer player to play the best move every time. *Note - I am not grading this for a correct answer, I just want to know your thoughts on how you might accomplish it. I will feed the the program multiple results foe each scenario and the outcome and which one would be the best move. As time goes on i will increas the difficlty of the scenarios and have the program determine the best scnarios for each.