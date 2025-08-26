# 🚢 Aaron's Battleship Game

**Author:** Aaron Dutta  
**Start Date:** July 22, 2024  

A simple Java console application that simulates the classic board game **Battleship**.  
The player and the computer take turns placing ships and firing missiles until one side sinks all of the other’s ships.

---

## 📖 Features

### 🎮 Gameplay
- Player and computer each have:
  - **Cruisers** (3 cells)
  - **Submarines** (3 cells)
  - **Carrier** (5 cells)
- Ships are placed on a **5x5 grid**.
- Player enters coordinates (e.g., `c3`) to launch missiles.
- Computer places ships randomly and makes random moves.

### 🧾 Rules & Input
- Input coordinates using **row + column** (e.g., `a1`, `c5`, `e3`).
- Rows are labeled **a–e** and columns **1–5**.
- Hits are marked with **H**, misses with **M**, and ships with **S**.
- The game ends when either the player or computer sinks **all 11 ship coordinates**.

### 📊 Statistics
At the end of the game, the program displays:
- Hits
- Misses
- Total moves

---

## 🖥️ Example Board

1 2 3 4 5
a . . . . .
b . . . . .
c . . . . .
d . . . . .
e . . . . .


- **S** → Ship  
- **H** → Hit  
- **M** → Miss  
- **.** → Empty cell  

---

## ⚙️ How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/Battleship-Game.git
Navigate into the project folder:

cd Battleship-Game
Compile the program:

javac Battleship.java
Run the program:

java Battleship
📌 Notes
User input is case-insensitive (A1 and a1 both work).

Invalid inputs are caught and prompt the user to try again.

The game is designed for a 5x5 grid (simplified version of classic Battleship).

✅ Example Output
less
Copy code
Welcome to Aaron’s Battleship Game!

Have you played battleship before (yes/no): no

Well then, I’ll show you the rules!
You have three different types of ships...
...
Please enter a coordinate to make a move: c3
Your move was a hit!
Computer’s move was a miss at b2.
🎯 Future Improvements
Add a difficulty system for the computer.

Implement larger grids (e.g., 10x10).

Save win/loss records.

