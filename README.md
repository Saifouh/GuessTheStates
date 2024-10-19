# U.S. States Guessing Game

This is a fun, interactive game that lets you guess the names of U.S. states on a blank map. It uses Python's Turtle graphics to display the map and pandas to track the guessed states.

## How to Play

- You'll be prompted to guess the name of a U.S. state.
- If you guess correctly, the state name will appear on the map.
- If you want to exit the game, type **Exit**. The game will then save a list of states you missed to a CSV file named `States_To_Learn.csv`.

## Installation and Requirements

To run the game, you need:
- Python 3.x
- `pandas` library
- `turtle` module (comes pre-installed with Python)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Saifouh/GuessTheStates.git
   ```
2. Install dependencies:
   ```bash
   pip install pandas
   ```
3. Run the game:
   ```bash
   python us_states_game.py
   ```

## Files

- **us_states_game.py**: Main game script.
- **assets/blank_states_img.gif**: U.S. map image.
- **assets/50_states.csv**: Coordinates of each state on the map.
- **States_To_Learn.csv**: Automatically generated list of missed states after the game.

## Demo

![Screenshot_580](https://github.com/user-attachments/assets/bf3879da-24d4-48c7-ae3d-d52a2e557276)


## License

This project is licensed under the MIT License.
