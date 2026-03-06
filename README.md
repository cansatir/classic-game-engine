# Classic Game Engine

A lightweight, modular, and extensible command-line game engine implemented in Python. 

## Overview
This project serves as a foundational engine for terminal-based games. It focuses on implementing core game architecture, including the **Game Loop** pattern, state management, and robust user input validation. 

## Features
- **Game Loop Architecture:** Implements a decoupled update-render cycle.
- **State Management:** Manages game transitions efficiently.
- **Input Handling:** Robust sanitization for user inputs to prevent runtime errors.
- **Modular Design:** Easily extensible to support new classic games.

## Project Structure
```text
classic-game-engine/
├── game.py          # Main entry point and game loop
└── engine/          # Core engine logic
    └── state.py     # State management
