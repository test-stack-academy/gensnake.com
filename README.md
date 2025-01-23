# GenSnake - Advanced AI Snake Game

## 🎮 Overview

GenSnake is a sophisticated implementation of the classic Snake game, enhanced with modern features like AI evolution, multiple snakes, real-time statistics, and a comprehensive development environment.

## ✨ Features

### Core Game Features

- 🐍 Multiple AI-controlled snakes with evolution mechanics
- 🧠 Four stages of AI evolution:
  - Basic: Random valid moves
  - Food-seeking: Moves towards food
  - Obstacle-avoidance: Avoids collisions
  - A* Pathfinding: Advanced route calculation
- 🍎 Dynamic food spawning system
- 📈 Snake splitting and growth mechanics
- ⚡ Variable speed based on snake length

### Advanced Features

- 📊 Real-time statistics and charts:
  - AI evolution progress
  - Performance metrics
  - Resource usage
  - Score tracking
  - Death rate analysis
- 🛠️ Built-in code editor with syntax highlighting
- 💬 AI-powered chat assistant
- 🌐 Network status monitoring
- ⚙️ Comprehensive settings system

### Technical Features

- 🎨 Dumb UI design
- 📱 Responsive design
- 🔧 Customizable controls
- 🏆 Achievement system
- 💾 Local storage for high scores
- 📊 Performance monitoring

## 🚀 Getting Started

### Running the Game

1. Download the HTML file
2. Open it in a modern web browser
3. Use arrow keys to control the player snake
4. Click on the game board to spawn new AI snakes

### Basic Controls

- Arrow Keys: Control snake direction
- R: Reset game
- +/-: Adjust game speed
- N: Toggle notifications
- S: Save code changes (with Ctrl)
- ,: Open settings

## 🎯 Game Mechanics

### Snake Behavior

- Snakes grow when eating food
- AI snakes evolve through different intelligence levels
- Snakes split when reaching certain length
- Natural decay over time if no food is eaten

### Scoring System

- Points awarded for eating food
- Bonus points for special achievements
- Multiplier system
- High score tracking

## ⚙️ Configuration

### Game Settings

- Board size (10-50)
- Initial speed (50-500ms)
- Split length (4-20)
- Maximum snakes (1-20)
- Food spawn interval (5-30)
- Decay interval (5-50)
- Speed factor (1-20)

### Advanced Settings

- Golden ratio for color generation
- Initial snake parameters
- Food positioning
- Control bindings
- Achievement settings
- Scoring parameters

## 📊 Statistics

### Real-time Monitoring

- CPU usage
- Memory consumption
- Network status
- Game metrics

### Performance Charts

- AI evolution progress
- Score progression
- Death rate analysis
- Food consumption rate

## 🛠️ Development

### Code Editor

- Built-in Ace editor
- JavaScript syntax highlighting
- Real-time code execution
- Auto-completion support

### Network Tools

- Connection status monitoring
- Speed measurement
- Data transfer tracking
- IP information

## 🏆 Achievements

- Speed Master: Reach maximum speed
- Snake Charmer: Grow to impressive length
- Food Champion: Collect 50+ food items
- AI Master: Evolve 3 snakes to maximum AI level

## 💻 Technical Requirements

### Browser Support

- Modern web browser with ES6+ support
- WebGL capability for graphics
- Local storage for saving progress
- Stable internet connection for chat features

### Recommended Specifications

- Display: 800x600 minimum resolution
- CPU: Modern dual-core processor
- RAM: 4GB minimum
- Storage: 50MB free space

## ⚠️ Known Limitations

- High CPU usage with multiple AI snakes
- Memory consumption increases over time
- Network features require internet connection
- Some features may be limited on mobile devices

## 🔄 Updates and Maintenance

### Current Version

- v0.4.2-dev

### Planned Features

- Additional AI evolution stages
- Multiplayer support
- More achievement types
- Enhanced visualization options

## 🤝 Contributing

While this is currently a self-contained project, suggestions and feedback are welcome through:

- Creating detailed bug reports
- Suggesting new features
- Sharing performance improvements
- Proposing AI enhancements

## 📝 License

This project is open-source and available under the MIT License.

## 👥 Credits

Developed as an advanced implementation of the classic Snake game, incorporating modern web technologies and AI concepts.

## 🔧 Troubleshooting

### Common Issues

1. Performance degradation
   - Reduce maximum snake count
   - Lower board size
   - Disable real-time statistics

2. High CPU usage
   - Limit AI snake count
   - Increase game speed interval
   - Close unnecessary browser tabs

3. Memory issues
   - Restart game periodically
   - Clear browser cache
   - Update browser

### Debug Mode

Press F12 to open browser developer tools for:

- Performance profiling
- Memory analysis
- Network monitoring
- Console debugging

## 📚 API Reference

### Game State Management

```javascript
resetGame()          // Reset game to initial state
updateBoard()        // Update game board display
handleSnakeDeath()   // Process snake death
generateFood()       // Create new food item
splitSnake()         // Handle snake splitting
```

### AI Functions

```javascript
getValidMoves()      // Get possible moves
getAIMove()          // Calculate AI move
findPathAStar()      // A* pathfinding
getFloodFill()      // Space calculation
```

### Utility Functions

```javascript
generateSnakeColor() // Generate unique colors
updateStatusBar()    // Update status display
handleCollision()    // Process collisions
updateHighScores()   // Update score records
```

## 🎨 Customization

### Visual Themes

Modify CSS variables for custom appearance:
```css
:root {
  --bg-primary: #ffffff;
  --accent-color: #424242;
  --border-color: #e7e7e7;
  /* Additional customization variables */
}
```

### Game Parameters

Adjust constants for different gameplay:
```javascript
BOARD_SIZE = 20;          // Grid size
INITIAL_SPEED = 200;      // Starting speed
SPLIT_LENGTH = 6;         // Split threshold
MAX_SNAKES = 10;          // Maximum snakes
```

## 🔍 Implementation Details

### AI Evolution System

1. Basic Movement
   - Random valid direction selection
   - Collision avoidance

2. Food Seeking
   - Distance calculation
   - Direct pathfinding

3. Obstacle Avoidance
   - Space evaluation
   - Risk assessment

4. A* Pathfinding
   - Optimal path calculation
   - Dynamic rerouting

### Performance Optimization

- Efficient grid updates
- Minimal DOM manipulation
- Throttled status updates
- Cached calculations

### Memory Management

- Periodic cleanup
- Resource monitoring
- Automatic garbage collection
- Data structure optimization

## 📱 Mobile Support

While primarily designed for desktop use, the game includes:

- Touch controls
- Responsive layout
- Adaptive UI
- Performance adjustments

## 🔐 Security

- Sandboxed execution
- Input validation
- Error handling
- Safe data storage

## 🎯 Future Development

### Planned Enhancements

1. Enhanced AI
   - Neural network integration
   - Learning algorithms
   - Behavior patterns

2. Multiplayer Features
   - Real-time competition
   - Leaderboards
   - Team modes

3. Visual Improvements
   - Additional themes
   - Particle effects
   - Animations

4. Performance Updates
   - WebAssembly integration
   - Worker threads
   - Optimization passes

---

*For the latest updates and information, check the game's built-in chat assistant or visit the statistics panel.*
