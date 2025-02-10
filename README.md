# Board Game Reservation System

This repository contains two versions of a board game reservation system:
1. **Board Game Reservation System.ipynb** - A simple reservation system implemented as a Jupyter Notebook.
2. **Board Game Reservation System_sqlite3.ipynb** - A version that integrates SQLite3 for database management, also in Jupyter Notebook format.

## Features
- **Check Available Games**: Lists all games that are not yet reserved.
- **Reserve a Game**: Users can reserve a game by specifying its name.
- **Cancel Reservation**: Users can cancel their reservation at any time.

## Installation & Usage

### Prerequisites
- Python 3.x
- Jupyter Notebook
- SQLite3 (for the SQLite version)

### Running the Program
1. Clone the repository or download the notebooks.
2. Open Jupyter Notebook and navigate to the desired `.ipynb` file.
3. Run the notebook cells to interact with the reservation system.

## Database Structure (SQLite3 Version)
- **reservation Table**
  - `id` (INTEGER, PRIMARY KEY): Unique game ID
  - `game` (TEXT): Game name
  - `user_id` (TEXT, NULLABLE): ID of the user who reserved the game

## Notes
- If a game is already reserved, users will be notified.
- If a reservation is successfully canceled, the system will confirm the cancellation.

## License
This project is open-source and available under the MIT License.

