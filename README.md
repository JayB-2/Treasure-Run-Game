# Treasure-Run-Game

Terminal-based dungeon crawler where players collect treasure, navigate rooms, and avoid obstacles. Features persistent player profiles, curses UI, and C-integrated game engine. Use WASD/arrows to move, find exits, and beat your high score.

## 📋 Features

### Features
- **MVC Architecture** - Clean separation between Model (data), View (UI), and Controller (game logic)
- **Player Profiles** - JSON-based persistence tracking games played, max treasure, and rooms completed
- **Curses UI** - Terminal-based interface with startup/quit splash screens and real-time gameplay
- **Game Runner** - Command-line interface with `--config` and `--profile` parameters

### Extended Features
- [ ] Collect All Treasures - Victory condition with progress tracking (e.g., "15/20 treasures")
- [ ] Enhanced UI - Color support and real-time minimap showing room graph

## 🎮 Controls

| Key | Action |
|-----|--------|
| `↑` `↓` `←` `→` or `W` `A` `S` `D` | Move player |
| `q` | Quit game |
| `r` | Reset game to beginning world state |

## 🚀 Installation & Setup

### Prerequisites
- Python 3.8+
- GCC (or any C compiler)
- Make
- curses library (included with Python on most Unix-like systems)
