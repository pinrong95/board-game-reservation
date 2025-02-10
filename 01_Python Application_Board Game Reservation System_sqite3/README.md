# Game Reservation System

This project is a simple game reservation system using SQLite. Users can check available games, make reservations, and cancel their reservations.

## Features
- **Initialize Game Data**: Creates a `reservation` table and adds sample games.
- **Check Available Games**: Lists all games that are not yet reserved.
- **Reserve a Game**: Users can reserve a game by specifying its name.
- **Cancel Reservation**: Users can cancel their reservation at any time.

## Installation & Usage

### Prerequisites
- Python 3.x
- SQLite3 (included with Python)

### Running the Program
1. Clone the repository or download the script.
2. Run the script using:
   ```bash
   Board Game Reservation System_sqite3.ipynb
   ```
3. Follow the prompts to interact with the reservation system.

### Commands
- **Show Available Games**: Type `Show game types`
- **Reserve a Game**: Type `I want to reserve <game name>`
- **Cancel Reservation**: Type `I want to cancel my reservation`
- **Exit the Program**: Type `End`

## Database Structure
- **reservation Table**
  - `id` (INTEGER, PRIMARY KEY): Unique game ID
  - `game` (TEXT): Game name
  - `user_id` (TEXT, NULLABLE): ID of the user who reserved the game

## Notes
- If a game is already reserved, users will be notified.
- If a reservation is successfully canceled, the system will confirm the cancellation.

## License
This project is open-source and available under the MIT License.

