# 🎮 Tetris Game in Python (Pygame)

[![Python](https://img.shields.io/badge/Python-3.6+-3776AB?logo=python)](https://www.python.org)
[![Pygame](https://img.shields.io/badge/Pygame-2.0+-00cc00)](https://www.pygame.org)

A classic single-player **Tetris game clone** built with **Python 3** and **Pygame** as part of a B.Sc. (Honours) final semester project at Panchmura Mahavidyalaya, Bankura University (2024–2025).  

This project showcases core game development concepts, including game loops, real-time rendering, object-oriented programming, user input handling, and graphical interface design.

---

## 📌 Table of Contents

- [🧩 Features](#-features)
- [📸 Screenshots](#-screenshots)
- [🚀 Getting Started](#-getting-started)
- [🎮 Controls](#-controls)
- [📁 Project Structure](#-project-structure)
- [💡 Educational Insights](#-educational-insights)
- [🛠️ Future Improvements](#-future-improvements)

---

## 🧩 Features

- ✅ Classic Tetris mechanics with smooth gameplay  
- 🔄 Tetromino rotation with shape-specific logic  
- ⬅️➡️ Horizontal movement and vertical descent  
- 🧠 Recursive line-clearing algorithm  
- 📈 Dynamic level progression (speed increases every 10 lines)  
- 🔽 Hard drop and ⬇️ soft drop mechanics  
- 🛑 Game Over detection with replay option  
- 🎨 Custom block rendering using image assets  
- 🖼️ User-friendly UI with score, level, and next-piece preview  
- 🧱 Modular, object-oriented design (`Tetris`, `Tetramino` classes)  
- 💻 Lightweight and cross-platform  

---

## 📸 Screenshots

![App Screen](app.png)

---

## 🚀 Getting Started

### 🔧 Prerequisites

- [Python 3.6+](https://www.python.org/downloads/)  
- [pip](https://pip.pypa.io/en/stable/installation/) (Python package manager)  
- [Pygame](https://www.pygame.org) (installed via pip)

### 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/python-tetris.git
   cd python-tetris
   ```

2. Create a virtual environment (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install pygame
   ```

### ▶️ Run the Game

```bash
python main.py
```

> **Note:** Ensure the `Assets/` and `Fonts/` folders are in the project directory, as they contain required image and font files.

---

## 🎮 Controls

| Key         | Function          |
|-------------|-------------------|
| `←` / `→`   | Move left/right   |
| `↑`         | Rotate tetromino  |
| `↓`         | Soft drop         |
| `Space`     | Hard drop         |
| `R`         | Restart game      |
| `P`         | Pause/Resume game |
| `Q` / `ESC` | Quit game         |

---

## 📁 Project Structure

```
├── Assets/               # PNG images for tetromino blocks
├── Fonts/                # Custom and system font files
├── main.py               # Main game source code
├── app.png               # Main game source code
└── README.markdown             # Project documentation (this file)
```

---

## 💡 Educational Insights

This project serves as both a playable game and an educational tool, demonstrating:

- ✅ Game loop architecture for real-time updates  
- ✅ Event-driven input handling with Pygame’s event queue  
- ✅ Object-oriented design with `Tetris` and `Tetramino` classes  
- ✅ Grid-based collision detection and movement logic  
- ✅ Recursive algorithms for clearing multiple lines  
- ✅ Dynamic score and level progression mechanics  
- ✅ Rendering with custom image assets via `pygame.Surface.blit()`  

---

## 🛠️ Future Improvements

- 🎵 Add background music and sound effects  
- 📜 Save high scores to a file or database  
- 📱 Support touch input for mobile devices  
- 🧠 Implement an AI opponent mode  
- 👥 Add multiplayer functionality  
- 🌈 Introduce custom themes and piece skins  
- 🌟 Enhance visuals for line clears and level-ups  
