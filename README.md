# PixelDraw – Multiplayer Online Pixel Art Board

## Description
PixelDraw is an interactive, real-time multiplayer pixel art application. It allows users to select colors and draw on a shared grid, with updates synchronized instantly across all connected users via WebSockets. Designed for creative collaboration and fun, it's suitable for developers learning real-time web development.

## Tech Stack
- Backend: Node.js, WebSocket
- Frontend: React
- Data Storage: (Optional) Persistence layer (e.g., file or database)

## Installation
1. Clone the repository:
```bash
git clone https://github.com/bitasmbl/pixel-draw-multiplayer-online-pixel-art-board.git
```
2. Navigate into the project directory:
```bash
cd pixel-draw-multiplayer-online-pixel-art-board
```
3. Install dependencies:
```bash
npm install
```

## Usage
### Run the server
```bash
node server.js
```
This starts the WebSocket server.

### Run the frontend
Navigate to the frontend directory (if separated) and start the React app: 
```bash
npm start
```
Open your browser to `http://localhost:3000` to see and participate in the collaborative pixel art board.

## Implementation Overview
- Users can select a color and click on pixels to draw.
- Pixel updates are broadcasted instantly to all users via WebSocket.
- The app tracks and displays the current number of active users.
- (Optional) Persist the canvas state to preserve artwork across sessions.

## When you are done, submit the project from your profile:
[https://bitasmbl.com/home/profile](https://bitasmbl.com/home/profile)