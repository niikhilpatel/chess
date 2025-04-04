# ♟ Real-Time Multiplayer Chess Game

A real-time multiplayer chess game built with Node.js, Socket.IO, and Chess.js. Players can drag and drop pieces, view captured pieces, and see whose turn it is. The UI is built using Tailwind CSS and supports spectator mode for additional users.

## 📸 Screenshots

### Game Interface

![image](https://github.com/user-attachments/assets/bd41ce60-e5df-4e7e-961d-b9d0fc33a7c3)

### Captured Pieces

![image](https://github.com/user-attachments/assets/76de1ad6-32e6-4f0e-825f-71cd45b782ce)


## 🚀 Features

- Real-time multiplayer gameplay using WebSockets
- Automatic player role assignment (white / black / spectator)
- Drag and drop movement using native HTML5 APIs
- Turn indicator to show who's playing
- Captured pieces display for both players
- Board auto-rotates for black player
- Clean and responsive UI with Tailwind CSS

## 🧠 Tech Stack

**Frontend:**
- HTML5 + Tailwind CSS
- JavaScript (Drag and Drop API)
- EJS Template Engine

**Backend:**
- Node.js
- Express.js
- Socket.IO (WebSocket communication)

**Game Logic:**
- [chess.js](https://github.com/jhlywa/chess.js) – for move validation and game state management

## 📦 Installation

```bash
git clone https://github.com/your-username/chess-game.git
cd chess-game
npm install
npm start
