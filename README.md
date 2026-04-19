![Python](https://img.shields.io/badge/Python-3.x-blue)

![License](https://img.shields.io/badge/License-MIT-green)

![Status](https://img.shields.io/badge/Project-Completed-brightgreen)


_**🎮 Simple Stone–Paper–Scissors Game (Python)**_


A beginner-friendly Python project that implements the classic Stone–Paper–Scissors game using modular programming. The game runs in a loop, allows multiple rounds, and determines the winner based on user and computer choices.

_**📌 Features**_

✅ Menu-driven user interaction

✅ Modular code using multiple Python files

✅ Random computer move generation

✅ Input validation for user entries

✅ Multiple rounds support

✅ Clear result display (Win / Lose / Draw)


_**🗂️ Project Structure**_

_**📁 Simple-Game**_

│── main.py        # Main game loop

│── user.py        # Handles user input

│── computer.py    # Generates computer choice

│── winner.py      # Determines the winner

│── util.py        # Stores game options

_**⚙️ How It Works**_

User selects an option (Stone, Paper, or Scissor)

Computer randomly selects its move

Winner is decided based on game rules

Result is displayed

User can choose to play another round

_**🧠 Game Logic**_

User Choice	Computer Choice	Result

Stone	Scissor	Win

Scissor	Paper	Win

Paper	Stone	Win

Same	Same	Draw

Otherwise	Otherwise	Lose

**▶️ How to Run**

Clone the repository:

git clone https://github.com/theneerajgrover/simple-game.git

Navigate to the project folder:

cd simple-game

**Run the game:**

python main.py

_**🧩 Module Breakdown**_

**🔹 main.py**

Controls the game loop

Calls functions from other modules

Handles replay logic

**🔹 user.py**

Takes user input

Validates input

Converts input into game choice

**🔹 computer.py**

Uses random module

Selects a random option from available choices

**🔹 util.py**

Stores list of valid options:

["Stone", "Paper", "Scissor"]

**🔹 winner.py**

Compares user and computer choices

Prints the result

📷 Sample Output

Select your Choice :

1. Stone

2. Paper
 
3. Scissor


ENTER YOUR CHOICE : 1

->You chose : Stone

->Computer chose : Paper

You Lost


Wanna play one more round ? (y/n)

_**🚀 Technologies Used**_

Python 3

Random Module

Modular Programming


_**📚 Concepts Covered**_

Functions

Loops (while loop)

Conditional statements (if-elif-else)

Input validation

Module importing

Code structuring

_**💡 Future Improvements**_

Add score tracking system

Add GUI (Tkinter / PyGame)

Add multiplayer mode

Improve UI with colors

Add sound effects

_**🧑‍💻 Author**_


Neeraj Grover

_**⭐ Support**_


If you like this project, give it a ⭐ on GitHub and share it with others!
