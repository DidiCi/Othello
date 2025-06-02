# ⚫️⚪ Othello Game Project

A multiplayer **Othello** board game built in Python 🐍 — playable through the terminal. This project is part of our team collaboration to learn Git and Python OOP.

---

## 📌 Project Overview

Othello is a classic strategy board game where two players take turns placing discs to capture the opponent's pieces. This project includes:

- A playable 8x8 grid
- Turn-based logic
- Valid move detection
- Disc flipping
- Win condition check
- An IA player

---

## 🧠 Goals

- Practice object-oriented programming in Python
- Learn and apply Git & GitHub workflows (branching, merging, PRs)
- Build a fully functional terminal-based board game

---

## 🗂️ Project Structure

<pre lang="markdown">  
  Othello/ 
  ├── engine/ 
  │   ├── __init__.py 
  │   └── othello.py # Game engine: controls game flow and rules 
  │ 
  ├── model/ 
  │ ├── __init__.py 
  │ ├── board.py # Board class: grid logic 
  │ ├── case.py # Case class: individual cell representation 
  │ ├── pawn.py # Pawn class: black/white disc logic 
  │ ├── player.py # Player class: player states 
  │ └── playerIA.py # PlayerIA class: define IA moves
  │ 
  ├── view/ 
  │ ├── __init__.py 
  │ ├── coordinates.py # Coordinate helper 
  │ └── display.py # Display logic (print board, status) 
  │ 
  ├── main.py # Game entry point 
  ├── .gitignore # Git ignored files 
  └── README.md # Project documentation 
  </pre>

---

## 🛠️ Setup

<pre lang="markdown">
git clone https://github.com/DidiCi/Othello.git
cd othello
python main.py
</pre>

---

## 👥 Contributors
- [@Poncet Ronan](https://github.com/PoncetRonan)
- [@Diletta Ciardo](https://github.com/DidiCi)
- [@Jip Wulffelé](https://github.com/JipWulffele)
- [@Jerome Delaunay](https://github.com/Jerome-Delaunay)

