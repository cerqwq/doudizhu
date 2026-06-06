# Doudizhu - Web Card Game

A web-based Doudizhu (Dou Di Zhu / Fight the Landlord) card game with AI opponents and online multiplayer support.

## Features

- Single-player mode with AI opponents
- Online multiplayer via WebSocket
- Player profiles and leaderboards
- Game history tracking
- Admin panel for management
- Responsive web UI

## Tech Stack

- **Backend:** Flask + Flask-SocketIO
- **Frontend:** HTML/CSS/JavaScript
- **Database:** SQLite
- **Real-time:** WebSocket

## Installation

```bash
pip install -r requirements.txt
```

## Usage

```bash
python app.py
```

Then open http://localhost:5000 in your browser.

## Game Rules

Doudizhu is a popular Chinese card game for 3 players. One player becomes the "landlord" (dizhu) and plays against the other two "farmers." The goal is to be the first to play all your cards.
