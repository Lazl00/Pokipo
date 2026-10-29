# Pokipo 🐤

**Pokipo** is a small 2D runner game written in **Python**, using **PyXRes** for graphics and input handling.

The goal is simple: **run, avoid obstacles, survive as long as possible and get the highest score possible.**

## 🎮 Features

- 🏃 Endless runner gameplay
- 🎨 2D graphics powered by **PyXRes**
- ⌨️ Keyboard controls
- 🧱 Obstacles to avoid
- 📈 Score progression
- 🔄 Restartable game loop
- 🐍 Written entirely in Python

## 🕹️ Controls

| Key | Action |
|---|---|
| `SPACE` | Jump |
| `ESC` | Quit |
| `R` | Restart after game over |

## 🚀 Installation

### Requirements

- Python 3
- PyXRes
- A compatible graphical environment

Clone the repository:

```bash
git clone <repository-url>
cd Pokipo
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

## ▶️ Run the game

Start Pokipo with:

```bash
python3 main.py
```

## 📁 Project structure

```text
Pokipo/
├── assets/
│   ├── sprites/
│   ├── backgrounds/
│   └── sounds/
├── src/
│   ├── player.py
│   ├── obstacle.py
│   ├── game.py
│   └── ...
├── main.py
├── requirements.txt
└── README.md
```

## 🧠 How it works

Pokipo is based on a classic **runner** game loop:

```text
Input
  ↓
Game update
  ↓
Collision detection
  ↓
Rendering
  ↓
Repeat
```

The player automatically moves forward while the environment scrolls around them.

As the game progresses, obstacles appear and the player must react quickly to avoid them. The score increases according to the player's progress.

## 🛠️ Technologies

- **Python 3**
- **PyXRes**
- 2D game development
- Object-oriented programming
- Event-driven game loop

## 🎯 Goal

Pokipo was created as a Python game project with a focus on:

- game-loop architecture
- keyboard input
- 2D rendering
- collision detection
- object management
- clean Python code

## 👥 Authors

Developed by the **Pokipo** team.

## 📄 License

This project is intended for educational and personal use.
