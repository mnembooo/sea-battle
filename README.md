# sea-battle

Overview
This Python script is a simple implementation of the classic Battleship board game. Players try to hit and sink ships placed randomly on a 7x7 grid by guessing their locations.

#Features
Text-based interface: The game features a simple text-based interface to interact with the player.
Random ship placement: Ships are placed randomly on the board at the start of the game.
Simple gameplay: Players enter coordinates to fire shots at the enemy ships.
Endgame detection: The game ends when all ships have been sunk.
#Requirements
Python 3.x
#How to Run the Game
Ensure Python 3.x is installed on your system.
Download the script to a directory on your machine.
Open a terminal or command prompt.
Navigate to the directory containing the script.
Run the script using the command python battleship.py (replace battleship.py with the actual script name).
Gameplay Instructions
Starting the Game: Enter your name when prompted.
#Playing the Game:
The game will display a 7x7 grid with columns labeled A-G and rows labeled 1-7.
Enter a coordinate (e.g., B3) to fire a shot at that location.
The grid updates after each shot, showing hits (X) and misses (O).
Winning the Game: The game ends when all parts of the ships are hit. Your performance is measured by the number of shots taken.
Replay Option: After a game ends, you can choose to play again.
#Game Mechanics
Ship Placement: Ships are placed randomly with varying sizes. The board ensures no overlapping or adjacent ships.
Shot Validation: The game checks for valid inputs (A1 to G7) and informs the player of invalid entries.
Hit Detection: The game updates the board based on whether a shot hits or misses.
