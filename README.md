# tic-tac-toe-with-python-AI-

# Tic Tac Toe with AI

A Python-based **Tic Tac Toe game** featuring multiple play modes and a strong, nearly unbeatable **AI opponent**. This project was created as part of a college AI and Python programming assignment.

---

## 🚀 Features

* **Player vs Player (PVP)** mode
* **Player vs AI** mode
* **AI vs AI** mode
* AI uses an **optimal strategy** (Minimax or equivalent)
* Console-based interface
* Clean and modular Python code structure
* Handles invalid inputs, win checks, and draw conditions

---

## 🧠 AI Logic

The AI is designed to be extremely difficult to beat. It analyzes all possible moves and selects the optimal one based on:

* Immediate winning moves
* Blocking the opponent’s winning move
* Evaluating board outcomes using a decision-making algorithm

Most commonly implemented using:

* **Minimax algorithm**
* Or **alpha‑beta pruning** for optimization

---

## 📁 Project Structure

```
TicTacToeAI/
├── main.py            # Entry point of the game
├── board.py           # Board display & management
├── game.py            # Game loop and modes
├── ai.py              # AI logic and minimax implementation
└── README.md          # Project documentation
```

*(Your actual file structure may differ depending on your implementation.)*

---

## ▶️ How to Run

1. Make sure you have **Python 3.x** installed.
2. Clone the repository:

```bash
git clone https://github.com/yourusername/TicTacToeAI.git
cd TicTacToeAI
```

3. Run the game:

```bash
python main.py
```

---

## 🎮 How to Play

After launching the program, select a mode:

* **1:** Player vs Player
* **2:** Player vs AI
* **3:** AI vs AI

The board updates after each move, and the game announces:

* Winner (X or O)
* Or a draw if the board is full

---

## 🧪 Testing

The project was tested for:

* All win conditions
* All draw conditions
* Proper AI behavior
* Input validation
* AI vs AI matches (almost always end in draws due to optimal play)

---

## 💡 Future Improvements

* Add a GUI (Tkinter or Pygame)
* Multiple difficulty levels
* Online multiplayer mode
* Sound effects & animations

---

## 📜 License

This project is open-source. You may use or modify it for personal or educational purposes.
