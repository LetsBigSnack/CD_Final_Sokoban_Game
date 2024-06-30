# Sokoban Console Game

Welcome to the Sokoban Console Game! This is a small .NET C# console application where you can enjoy solving Sokoban puzzles with added functionalities such as undo/redo, saving/loading game states, and a timer to challenge your skills.

## Features

- **Three Levels**: Enjoy three challenging levels to test your puzzle-solving skills.
- **Undo/Redo Moves**: Use LINQed lists to undo and redo your moves.
- **Save/Load Game State**: Save your current game state and load it later to continue your progress.
- **Game Timer**: Complete the level before the timer runs out to win the game.

## Controls

- **Move**: Arrow Keys
- **Tutorial Dialogue**: Spacebar
- **Undo Move**: `CTRL + Z`
- **Redo Move**: `CTRL + Y`
- **Save Game**: `CTRL + S`
- **Reload Game from Save**: `CTRL + R`
- **Close Game**: `CTRL + X`

## Setup and Running the Game

1. **Clone the Repository**: 
   ```sh
   git clone https://github.com/LetsBigSnack/CD_Final_Sokoban_Game.git
   ```

2. **Set Environment Variable**:
   - Open the environment variables settings in Windows.
   - Add a new variable `GAME_SETUP_PATH` and set its value to `Setup.json` in the project directory.
   - Close and restart Visual Studio to apply the changes.

3. **Navigate to the Game Directory**:
   ```sh
   cd game
   ```

4. **Run the Game**:
   ```sh
   dotnet run
   ```

## Acknowledgements

We already finished the whole project previously as a DEDI Group.
