# 🐍 Snake Game

[![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Pygame](https://img.shields.io/badge/Pygame-2.x-green?logo=pygame&logoColor=white)](https://www.pygame.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A classic Snake game built with Python and Pygame. Guide the snake to eat food, grow longer, and rack up the highest score — without running into the walls or yourself!

---

## 🎮 Demo

```
┌──────────────────────┐
│  Score: 5            │
│                      │
│       ██             │
│     ████             │
│       ██    🍎       │
│                      │
└──────────────────────┘
```

---

## ✨ Features

- Smooth, real-time keyboard controls
- Score tracking displayed on screen
- Automatic game reset on collision (walls or self)
- Food spawns randomly, never on the snake's body
- Lightweight — runs at a fixed 15 FPS for consistent speed

---

## 📋 Prerequisites

- **Python 3.x** — [Download](https://www.python.org/downloads/)
- **Pygame** library

---

## 🚀 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/xainy75/snakegame.git
   cd snakegame
   ```

2. **Install Pygame**
   ```bash
   pip install pygame
   ```

3. **Run the game**
   ```bash
   python snakegame.py
   ```

---

## 🕹️ Controls

| Key | Action |
|-----|--------|
| ⬆️ Arrow Up | Move Up |
| ⬇️ Arrow Down | Move Down |
| ⬅️ Arrow Left | Move Left |
| ➡️ Arrow Right | Move Right |

---

## 📐 Gameplay

| Detail | Value |
|--------|-------|
| Window Size | 400 × 400 px |
| Grid Size | 20 × 20 px cells |
| Speed | 15 FPS |
| Snake Color | 🟩 Green |
| Food Color | 🟥 Red |

- **Eating food** — the snake grows by one segment and the score increases by 1.
- **Wall or self-collision** — the game resets and the score returns to 0.

---

## 📁 Project Structure

```
snakegame/
├── snakegame.py   # Main game logic
└── README.md      # Project documentation
```

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add your feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

<p align="center">Made with ❤️ and Python</p>