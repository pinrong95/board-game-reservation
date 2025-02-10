Game Reservation System
This program is a simple game reservation system using an SQLite database to store game data. Users can query available games, make reservations, or cancel existing reservations.

Features
Initialize Game Data: The program creates a reservation table in the database and inserts a few games.
Query Available Games: When the user sends the message "Show game types", the system returns the list of games that are available for reservation.
Reserve a Game: The user can send the message "I want to reserve <game name>" to reserve a game. If the game is not yet reserved, the system will reserve it for the user.
Cancel Reservation: The user can send the message "I want to cancel my reservation" to cancel all of their reservations.
Installation and Usage
1. Install Python and SQLite
This program requires Python 3.x and the SQLite library. If Python is not installed, visit the official Python website to download and install it.

2. Run the Program
Download or copy this program.
Run the program in the command line or terminal:
bash
複製
編輯
python game_reservation.py
Follow the prompts to interact with the system.
3. Feature Operations
Query Available Games: Type Show game types to see the available games for reservation.
Reserve a Game: Type I want to reserve <game name>, for example, I want to reserve Little Valon.
Cancel Reservation: Type I want to cancel my reservation to cancel all reservations.
4. Exit the Program
Type End to stop the program.

Parameter Explanation
user_id: Each user has a unique user_id to identify and manage their reservations.
game: The name of the reserved game.
Database Structure
The reservation table has the following columns:
id: Unique identifier for each game.
game: Name of the game.
user_id: Unique identifier for the user. If the game is not reserved, it is NULL.
Notes
When a game is already reserved by another user, the system will respond with "This game is already reserved! Sorry".
If the reservation is successfully canceled, the system will respond with "Your reservation has been canceled".
I hope this English README is helpful for users to understand how to use your program! Let me know if you need further adjustments or additions.