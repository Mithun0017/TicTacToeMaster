# 🎯 Tic Tac Toe (Tkinter GUI)

A classic two-player Tic‑Tac‑Toe game with a clean, clickable GUI built using **Tkinter**. Playable on the same machine, with logic for win detection, draw handling, and easy resetting.

---

## 🕹 How to Play

1. Players take turns clicking empty cells to place **X** or **O**.
2. The game automatically toggles between players.
3. A winning line (horizontal, vertical, or diagonal) turns **green**.
4. If the board fills without a winner, all cells highlight **yellow** to indicate a draw.
5. Click **Restart** to clear the board and play again.

---

## ✨ Features

- **Intuitive GUI** — grid-based layout with responsive visual cues  
- Automatically switches turns between players  
- Highlights winning line or draws for clear feedback  
- Reset button for quick replay  
- Random starting player adds variety each round

---

## 📂 Project Structure

```
├── Tic-Tac-Toe.py          # Tkinter Tic‑Tac‑Toe implementation
├── tic-tac-toe-icon.png    # Window icon
└── README.md               # This file
```

---

### 🛠️ How It Works

- **Grid setup**: A 3×3 grid of `Button` widgets is dynamically created inside a loop and assigned `lambda` callbacks to handle cell clicks, allowing each button to call `next_turn(row, column)` when clicked. This pattern is commonly used in Tkinter-based Tic-Tac-Toe implementations.

- **Game logic**: The `check_winner()` function evaluates all possible winning combinations—rows, columns, and diagonals—to detect a win. When a winner is found, the corresponding buttons' background colors are updated. A tie is handled by checking for no remaining empty spaces.

- **Restart functionality**: The "Restart" button triggers the `new_game()` function, which clears all cell texts and resets backgrounds, then randomly selects the starting player, allowing for a fresh round.

---

## 📸 Screenshots

<p float="left">
  <img src="./Output Screenshots/Tic_Tac_Toe_2.png" width="48%" />
</p>

---

## 📫 Contact

- **GitHub**: [@Mithun0017](https://github.com/Mithun0017)  
- **Email**: [mithun200617@gmail.com](mailto:mithun200617@gmail.com)

---
