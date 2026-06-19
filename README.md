# 💣 Minesweeper Explorer

A unique take on the classic Minesweeper formula where you don't click tiles—you explore the board as a character.

Navigate the minefield, jump across tiles, place flags, and reveal cells while physically moving around the map. The project combines traditional Minesweeper mechanics with character movement and light platforming elements.

---

## 🎮 Features

### Core Gameplay

* Classic Minesweeper rules
* Character-based exploration
* Keyboard-only gameplay
* Randomly generated minefields
* Automatic flood-fill revealing
* Mine flagging system
* Win and lose states

### Game Modes

| Mode         | Grid Size | Mines |
| ------------ | --------- | ----- |
| Beginner     | 9 × 9     | 10    |
| Intermediate | 16 × 16   | 40    |
| Expert       | 30 × 16   | 99    |

### Character System

* Grid-based movement
* Jump mechanic
* Dash movement
* Character animations
* Multiple unlockable skins
* Visual tile highlighting

### Visual Effects

* Smooth camera tracking
* Landing particles
* Dash trails
* Screen shake effects
* Retro pixel-art inspired UI
* Animated tile reveals

### Additional Features

* Daily Challenge Mode
* Local progress saving
* Timer system
* Mine counter
* Pause menu
* Character skin unlocks

---

## 🎯 Objective

Reveal all safe tiles without triggering a mine.

You can:

* Move using the keyboard
* Stand on a tile
* Reveal it
* Flag suspected mines
* Clear the entire board

Victory is achieved when all safe tiles have been revealed.

---

## ⌨ Controls

| Key        | Action            |
| ---------- | ----------------- |
| W A S D    | Move              |
| Arrow Keys | Move              |
| Space      | Jump              |
| E          | Reveal Tile       |
| F          | Place/Remove Flag |
| Shift      | Dash              |
| R          | Restart           |
| Esc        | Pause             |

---

## 🕹 How To Play

1. Select a difficulty.
2. Move your character around the board.
3. Stand on a tile.
4. Press **E** to reveal it.
5. Use the numbers to determine nearby mines.
6. Mark suspected mines with **F**.
7. Reveal all safe tiles to win.

---

## 🏆 Unlockable Skins

Complete boards to unlock new character skins.

* Green (Default)
* Blue
* Red
* Gold

Higher difficulties unlock rarer skins.

---

## 🛠 Technical Overview

### Built With

* HTML5
* CSS3
* JavaScript (Vanilla)
* HTML Canvas API
* Web Audio API
* Local Storage API

### Systems

* Minefield Generator
* Flood Fill Reveal Logic
* Character Controller
* Camera System
* Particle System
* Audio Manager
* Save System
* UI Manager

---

## 📸 Screenshots

Add screenshots here.

```md
![Gameplay](screenshots/gameplay.png)
![Victory](screenshots/victory.png)
![Daily Challenge](screenshots/daily.png)
```

---

## 🚀 Running Locally

Clone the repository:

```bash
git clone https://github.com/yourusername/minesweeper-explorer.git
cd minesweeper-explorer
```

Open:

```bash
index.html
```

or run a local server:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

---

## 📜 License

MIT License

Feel free to modify, improve, and distribute the project.

---

## 💡 Inspiration

Inspired by the idea of turning a traditionally mouse-driven puzzle game into a character-driven exploration experience. Instead of clicking squares, players physically navigate the minefield, making movement part of the challenge.
