# 🟢⚪ Othello Game Project

A multiplayer **Othello** board game built in Python 🐍 — playable through the terminal. This project is part of our team collaboration to learn Git and Python OOP.

---

## 📌 Project Overview

Othello is a classic strategy board game where two players take turns placing discs to capture the opponent's pieces. This project includes:

- A playable 8x8 grid
- Turn-based logic
- Valid move detection
- Disc flipping
- Win condition check

---

## 🧠 Goals

- Practice object-oriented programming in Python
- Learn and apply Git & GitHub workflows (branching, merging, PRs)
- Build a fully functional terminal-based board game

---

## 🗂️ Project Structure

Othello/
├── engine/
│ ├── init.py
│ └── othello.py # Game engine: controls game flow and rules
│
├── model/
│ ├── init.py
│ ├── board.py # Board class: grid logic
│ ├── case.py # Case class: individual cell representation
│ ├── pawn.py # Pawn class: black/white disc logic
│ ├── player.py # Player class: player states
│ └── noPawnError.py # Custom error for missing pawns
│
├── view/
│ ├── init.py
│ ├── coordinates.py # Coordinate helper/conversion
│ └── display.py # Display logic (print board, status)
│
├── main.py # Game entry point
├── .gitignore # Git ignored files
└── README.md # Project documentation

---

## 🛠️ Setup
git clone https://github.com/your-username/othello.git
cd othello
python main.py

---

## 👥 Contributors
@
@
@
@

