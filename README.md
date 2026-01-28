# Human-vs-AI-chess-game
A Human vs AI Chess Game built in Python using object-oriented design. Core chess logic is implemented through modular classes. The AI uses Minimax with Alpha–Beta Pruning and heuristic evaluation. The game supports legal moves, special rules, end-game detection, and a GUI.

# ♟️ Human vs AI Chess Game (Python)

## 📌 Project Overview

This project is a **Human vs AI Chess Game** implemented in **Python** using an **Object-Oriented Programming (OOP)** approach. The AI opponent uses the **Minimax algorithm with Alpha–Beta Pruning** to make strategic decisions. The game supports complete chess rules, special moves, and end-game detection, along with a GUI for interactive play.

---

## 🧠 Key Features

* Object-oriented design with modular classes
* AI opponent powered by Minimax + Alpha–Beta Pruning
* Heuristic evaluation (piece weights, king safety, positional advantage)
* Turn-based gameplay (Human vs AI)
* Legal move generation
* Special moves:

  * Castling
  * Pawn Promotion
  * En Passant
* End-game detection:

  * Check
  * Checkmate
  * Stalemate
* Graphical User Interface (GUI)

---

## 🏗️ Project Structure

```
ChessGame
├── ChessGame       # Main game loop and control logic
├── Board           # Board representation and state management
├── Move            # Move abstraction
├── Piece           # Abstract base class for pieces
├── King
├── Queen
├── Rook
├── Bishop
├── Knight
├── Pawn
├── Player          # Abstract player class
├── HumanPlayer
├── AIPlayer        # Minimax + Alpha–Beta Pruning
├── Evaluation      # Board evaluation heuristics
└── main            # Entry point
```

---

## 📚 Required Libraries

Make sure the following libraries are installed:

* **Python 3.8 or higher**
* `tkinter` – for GUI (comes pre-installed with Python)
* `copy` – for deep copying board states
* `math` – for Minimax scoring

> No external third-party libraries are required.

---

## ⚙️ Environment Setup

### 1️⃣ Install Python

Download and install Python from:
[https://www.python.org/downloads/](https://www.python.org/downloads/)

Make sure to check **"Add Python to PATH"** during installation.

### 2️⃣ Verify Installation

```bash
python --version
```

---

## ▶️ How to Run the Game

1. Clone or download the project folder
2. Navigate to the project directory:

```bash
cd Human-vs-AI-Chess
```

3. Run the main file:

```bash
python main.py
```

---

## 🎮 How to Play

* **Human Player:** White pieces
* **AI Player:** Black pieces
* Click or input moves according to the GUI instructions
* The AI automatically responds after each human move
* The game ends when a **checkmate** or **stalemate** is detected

---

## 🤖 AI Details

* Algorithm: **Minimax with Alpha–Beta Pruning**
* Search Depth: 3 levels
* Evaluation Criteria:

  * Material balance (piece values)
  * King safety
  * Positional advantage

---

## 🧪 Tested On

* Windows 10 / 11
* Python 3.9+

---

## 📌 Author

**Ayesha Areej**
Bachelor’s in Cyber Security
---

## 📄 License

This project is for **educational purposes only**.
