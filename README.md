# Collaborative Whiteboard with Real-Time Drawing

A real-time collaborative whiteboard that allows multiple users to draw and interact in shared rooms.

## ◆ Features
- Real-time drawing
- Room creation and joining
- Multiple drawing tools
- Colour selection
- Undo and redo
- Canvas clearing
- PNG export
- Drawing persistence

## ⚙ Tech Stack
- HTML, CSS, JavaScript
- Node.js and Express.js
- WebSockets
- Firebase Firestore
- Render

## ⚙ Local Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/Vibha-maker/Collaborative-Whiteboard-with-real-time-drawing.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Collaborative-Whiteboard-with-real-time-drawing
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Configure Firebase environment variables:
   - `FIREBASE_PROJECT_ID`
   - `FIREBASE_SERVICE_ACCOUNT`

5. Start the server:
   ```bash
   npm start
   ```

> **Note:** Valid Firebase credentials are required to run the application.

## ➜ Deployment

**Live Demo:** https://collaborative-whiteboard-oa2n.onrender.com

## ▣ Project Structure

```text
├── public/
│   ├── index.html
│   ├── whiteboard.html
│   ├── whiteboard.js
│   ├── whiteboard-style.css
│   ├── script.js
│   └── style.css
├── .gitignore
├── server.js
├── rooms.json
├── package.json
├── package-lock.json
└── README.md
```

## # API Endpoints

- `GET /` - Home page
- `POST /api/rooms` - Create room
- `GET /api/rooms/:id` - Get room details
- `GET /whiteboard/:roomId` - Access whiteboard

## ◈ WebSocket Events

- `join_room` - Join room
- `drawing_data` - Share drawing updates
- `user_joined` - User joined notification
- `user_left` - User left notification

## ◇ Contributing

1. Fork the repository
2. Create a feature branch
3. Make changes
4. Test the application
5. Submit a pull request
