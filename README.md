# 🏓 Multiplayer Pong Master

A real-time multiplayer implementation of the classic Pong game built with modern web technologies. Experience the nostalgia of Pong with friends across the internet!

![Game Preview](https://img.shields.io/badge/Status-Active-brightgreen) ![Version](https://img.shields.io/badge/Version-1.0-blue) ![License](https://img.shields.io/badge/License-MIT-yellow)

## 🎮 Features

- **Real-time Multiplayer**: Play against friends or strangers online
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Smooth Gameplay**: 60 FPS game loop with collision detection
- **Real-time Sync**: Server-side game state management prevents cheating
- **Lobby System**: Create or join game rooms
- **Score Tracking**: Keep track of wins and losses
- **Spectator Mode**: Watch ongoing matches
- **Low Latency**: Optimized for minimal input lag

## 🚀 Demo

[Live Demo](https://your-demo-link.com) | [Video Preview](https://your-video-link.com)

## 🛠️ Tech Stack

### Frontend
- **HTML5 Canvas**: For game rendering
- **JavaScript (ES6+)**: Game logic and client-side interactions
- **CSS3**: Responsive styling and animations
- **Socket.IO Client**: Real-time communication

### Backend
- **Node.js**: Server runtime
- **Express.js**: Web framework
- **Socket.IO**: WebSocket implementation for real-time communication
- **UUID**: Unique room and player identification

### Additional Tools
- **npm**: Package management
- **Nodemon**: Development server auto-restart
- **ESLint**: Code linting and formatting

## 📦 Installation

### Prerequisites
- Node.js (v14.0.0 or higher)
- npm (v6.0.0 or higher)

### Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/Kellysabi/multiplayer-pong-master.git
   cd multiplayer-pong-master
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm start
   ```

4. **Open your browser**
   ```
   http://localhost:3000
   ```

### Production Deployment

1. **Build for production**
   ```bash
   npm run build
   ```

2. **Start production server**
   ```bash
   npm run prod
   ```

## 🎯 How to Play

1. **Create or Join a Room**: Enter a room name or join an existing one
2. **Wait for Opponent**: Share the room code with a friend or wait for matchmaking
3. **Game Controls**:
   - **Player 1**: `W` (up) / `S` (down)
   - **Player 2**: `↑` (up) / `↓` (down)
   - **Mobile**: Touch controls on screen
4. **Objective**: Be the first to score 11 points!

## 🏗️ Project Structure

```
multiplayer-pong-master/
├── public/
│   ├── index.html          # Main HTML file
│   ├── css/
│   │   └── style.css       # Game styling
│   ├── js/
│   │   ├── game.js         # Client-side game logic
│   │   ├── ui.js           # User interface management
│   │   └── socket.js       # Socket.IO client setup
│   └── assets/
│       └── sounds/         # Game sound effects
├── server/
│   ├── server.js           # Express server setup
│   ├── game/
│   │   ├── GameRoom.js     # Game room management
│   │   ├── Player.js       # Player object model
│   │   └── Ball.js         # Ball physics and movement
│   └── utils/
│       └── helpers.js      # Utility functions
├── package.json
├── README.md
└── .gitignore
```

## 🔧 Configuration

### Environment Variables

Create a `.env` file in the root directory:

```env
PORT=3000
NODE_ENV=development
MAX_ROOMS=100
MAX_PLAYERS_PER_ROOM=2
GAME_SPEED=60
```

### Game Settings

Modify `config/gameConfig.js` to adjust:
- Ball speed and acceleration
- Paddle size and speed
- Canvas dimensions
- Scoring system

## 🤝 Contributing

We welcome contributions! Here's how to get started:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'Add amazing feature'
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/amazing-feature
   ```
5. **Open a Pull Request**

### Development Guidelines

- Follow ES6+ JavaScript standards
- Use meaningful variable and function names
- Add comments for complex game logic
- Test multiplayer functionality thoroughly
- Ensure mobile responsiveness

## 🐛 Known Issues

- [ ] Occasional desync in high-latency connections
- [ ] Mobile touch controls need refinement
- [ ] Spectator mode UI improvements needed

## 🚀 Roadmap

- [ ] **Tournament Mode**: Multi-player tournaments
- [ ] **Power-ups**: Special abilities and effects
- [ ] **Customization**: Paddle colors and themes
- [ ] **Statistics**: Detailed player analytics
- [ ] **Replay System**: Save and watch game replays
- [ ] **AI Opponent**: Single-player vs computer
- [ ] **Mobile App**: Native iOS/Android versions

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by the original Pong by Atari (1972)
- Socket.IO community for excellent real-time communication tools
- Contributors and testers who helped improve the game

## 📞 Support

- **Issues**: [GitHub Issues](https://github.com/Kellysabi/multiplayer-pong-master/issues)
- **Discussions**: [GitHub Discussions](https://github.com/Kellysabi/multiplayer-pong-master/discussions)
- **Email**: kelly@example.com

---

⭐ **Star this repo if you enjoyed playing!** ⭐

**Built with ❤️ by [Kelly Sabi](https://github.com/Kellysabi)**
