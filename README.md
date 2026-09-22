 **Tic Tac Toe Game**

A simple and interactive Tic Tac Toe game built using HTML, CSS, and JavaScript.
This project demonstrates core concepts of DOM manipulation, event handling, and game logic implementation.

__Features__
 * Two-player game (X vs O)
 * Interactive UI using buttons
 * Winner detection logic
 * Reset game functionality
 * New game option
 * Clean and responsive layout

🧰 Technologies Used
i) HTML5 – Structure of the game
ii) CSS3 – Styling and layout
iii) JavaScript – Game logic and interactivity

📂 Project Structure
tic-tac-toe/
│
├── tic.html
├── tic.css
└── tic.js


 How the Game Works
1️⃣ Game Board
The board consists of 9 buttons (3x3 grid)
Each button represents a cell

2️⃣ Player Turns
Player O starts first
Players take turns marking:
i)        O
ii)       X

3️⃣ Winning Logic
Winning patterns are defined as:
[0,1,2], [0,3,6], [0,4,8],
[1,4,7], [2,5,8], [2,4,6],
[3,4,5], [6,7,8]

The game checks if any of these patterns match after every move.

4️⃣ Winner Display
Displays message:
Congradulations, Winner is X/O
Game stops after winner is found

5️⃣ Reset Functionality
Reset Button → Clears board
New Game Button → Starts fresh game

⚙️ How to Run
Download or clone the repository:
git clone https://github.com/idrisrazaballry/tic-tac-toe.git

Open the project folder
Run the game:
Open tic.html in browser

_Key Concepts Used_
DOM Selection (querySelector, querySelectorAll)
Event Listeners
Game State Management
Arrays for winning logic
Dynamic UI updates

__Future Improvements__
Add draw detection
Add score tracking
Add AI (play vs computer)
Improve UI animations
Make it mobile responsive
