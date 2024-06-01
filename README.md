# Codsoft-Task1
# NUMBER GUESSING GAME

********Overview of the project*******

1. *Introduction*: The game starts with a welcoming message "Welcome to the Guessing Game!"

2. *Setup*: 
   - It initializes a Scanner object for user input.
   - It initializes a Random object to generate random numbers.

3. *Game Loop*: 
   - The game loop allows the player to play multiple rounds until they decide to stop.
   - Inside the loop, a random number is generated between the specified range (1 to 100).
   - The player is prompted to guess the number.

4. *Guessing Mechanism*: 
   - The player's guess is compared with the randomly generated number.
   - If the guess matches the number, the player is congratulated, and their score is incremented.
   - If the guess is too high or too low, the player is given a hint and prompted to guess again.

5. *Score Tracking*: 
   - The player's score is incremented each time they guess the correct number.
   - The current score is displayed after each round.

6. *Play Again*: 
   - After each round, the player is asked if they want to play again.
   - If the player chooses to play again, the loop continues; otherwise, the game ends.

7. *Conclusion*: 
   - When the player decides to stop playing, a closing message is displayed along with their final score.
   - The Scanner is closed to release system resources.

Overall, this program creates a simple guessing game where players try to guess a randomly generated number within a specified range. It provides feedback on each guess and keeps track of the player's score throughout the game.