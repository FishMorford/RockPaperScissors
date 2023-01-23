# RockPaperScissors
This repo consists of the classic game: Rock Paper Scissors.
You will play first to 3 points against the CPU.

To play the game:
- Clone this Repo.
- Make sure you have Visual Studio installed.
- Open the .sln file in: ...\RockPaperScissors\RockPaperScissors ("..." being where you saved the Repo).
- Click Build > Build RockPaperScissors.

- In File Explorer, navigate to where you cloned the Repo
- Go to : ...\RockPaperScissors\RockPaperScissors\RockPaperScissors\bin\Debug
- Run the .exe to play.

Alternatively, after opening the .sln file in Visual Studio, just click Ctrl + F5.

# Playing the Game

The game will ask you to choose between Rock, Paper and Scissors.
- Type your answer.
- The CPU will choose its own answer and show it to you and then will compare the 2 choices.
- If you typed something other than rock, paper or scissors, the computer will tell you to try again and no points will be awarded.
- Once you have correctly chosen an answer, the computer will compare the answers and award a point based on the basic rules of the game (see below).
- The first to get 3 points will win the game!
- At the end of the game, you will be asked if you would like to play again.
- Select an option to either restart the game or close the program.

# Game Rules
- Rock beats Scissors
- Scissors beats Paper
- Paper beats Rock
- Winning a round awards 1 point
- A Draw results in no points being awarded
- The first player to reach 3 points wins the game

# Project Notes
Just like my Number Guessing Game, this project is a ConsoleApplication using C#.
Learning from my previous project, I made a very similar system that uses a Random Number Generator to choose Rock, Paper or Scissors.
The player then inputs their choice and the system now accounts for mispelt words and case sensitivity.
The computer compares answers and awards points accordingly using a case statement this time instead of nested if statements.
